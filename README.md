# oicp-cpo-2.3-api-doc

## Requirements

To build project you need to have `node` installed.

## Install

To install dependencies run `npm install`

## Build

To build OpenAPI specification file run `npm run build`

Documentation can be linted using `npm run test`

Compiled documentation can be previewed using `npm run preview`

## GitHub Pages

Page is hosted using `index.html`, `openapi.yaml` and `images/` from the main project directory.
`openapi.yaml` file is created during build process and it should be commited together with change done to the source code of the documentation, this way changes will be visible to GitHub Pages as well.  