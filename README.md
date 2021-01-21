# Introduction

This repository contains OpenAPI specifications for the Digital Site Logistics Standard APIs.

# Generating code & documentation

## Installation
* Install Java 1.8 or later, make sure `java.exe` is found in the PATH
* Install NodeJS 14

After cloning the repository, run `npm install`.

## Running the generator
Run `npm run {generator}` where generator is one of

* `redoc` - recommended, generates a nice HTML documentation
* `openapi` - converts the YAML to JSON

Other less useful generators are also defined in `package.json`.

See [https://openapi-generator.tech/docs/generators/](https://openapi-generator.tech/docs/generators/) for the list of generators supported.

## Printing the Redoc documentation
If you want to print the redoc documentation, expand all schema items first with this script.
```
document.querySelectorAll("[aria-label='expand properties']").forEach(b => b.click());
```

Use Chrome, the printed from Firefox doesn't look right.

## Generating a PDF
Make the YAML file available through HTTP, for example by uploading it as a Github Gist.

Then, use the public URL of your YAML at [RapiPdf](https://mrin9.github.io/RapiPdf/).