Prerequisites
===============
* Install Java 1.8 or later, make sure `java.exe` is found in the PATH
* Install NodeJS 14

Installation
==============
After cloning the repository, run `npm install`.

Generating documentation
==========================
Run `npm run {generator}` where generator is one of

* redoc - recommended, generates a nice HTML documentation
* openapi - converts the YAML to JSON

Other less useful generators are also defined in `package.json`.

Generating a PDF
=================
* make the YAML file available through HTTP, for example by uploading it as a Github Gist.
* Use the public URL at [RapiPdf](https://mrin9.github.io/RapiPdf/)
