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

* `redoc` - recommended, generates a nice HTML documentation
* `openapi` - converts the YAML to JSON

Other less useful generators are also defined in `package.json`.

Printing the Redoc documentation
==================================
If you want to print the redoc documentation, expand all schema items first with this script.
```
document.querySelectorAll("[aria-label='expand properties']").forEach(b => b.click());
```

Use Chrome, the printed from Firefox doesn't look right.

Example objects won't be printed.

Generating a PDF
=================
Make the YAML file available through HTTP, for example by uploading it as a Github Gist.

Then, use the public URL of your YAML at [RapiPdf](https://mrin9.github.io/RapiPdf/).
