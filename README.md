# Introduction

This repository contains OpenAPI specifications for the Digital Site Logistics Standard APIs.

# Generating code & documentation

## Installation
* Install Java 1.8 or later, make sure `java.exe` is found in the PATH
* Install NodeJS 14

After cloning the repository, run `npm install`.

## Regenerating the documentation

Download `swagger.json` from the DTLS API, it can be found on the path `/swagger/vXX/swagger.json`.
Where vXX is the API version, currently v15.

Run `npm run redoc`, the documentation will be at `docs\index.html`. 
