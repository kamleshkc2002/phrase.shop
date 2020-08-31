# phrase.shop #

[**phrase.shop**](https://phrase.shop) is a small web app to generate secure yet memorable passphrases.

## Prerequisites

Install [`npm`](https://www.npmjs.com/) using whatever
means is most convenient for you, such as [Homebrew](https://brew.sh/) on macOS.

## Initialization

    $ npm install
 
This creates a `node_modules` directory.

## Unit-test

    $ npm test

## View locally

    $ npm start

And your browser will magically open to the web app.
This supports hot-reloading, so feel free to edit Javascript and see your changes
in the browser immediately.

The other way that works is to build the app explicitly (`npm run build`), then
simply open _index.html_ from the local filesystem in the browser.

## Publish to the Internet

Build:

    $ npm run build

This will create `web/app.bundle.js`.

Then upload the contents of `web/` to your web host.

# React/TS template #

The React/TS template for this web app came from https://github.com/philipmw/spa-template.