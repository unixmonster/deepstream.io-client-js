deepstream.io-client-js
=======================
[![Build Status](https://travis-ci.org/deepstreamIO/deepstream.io-client-js.svg?branch=master)](https://travis-ci.org/deepstreamIO/deepstream.io-client-js) [![Coverage Status](https://coveralls.io/repos/github/deepstreamIO/deepstream.io-client-js/badge.svg?branch=master)](https://coveralls.io/github/deepstreamIO/deepstream.io-client-js?branch=master) [![npm version](https://badge.fury.io/js/%40deepstream%2Fclient.svg)](https://badge.fury.io/js/%40deepstream%2Fclient)


The Browser / Node Client for [deepstream.io](http://deepstream.io/)

## Documentation

For API documentation see the [documentation page](http://deepstream.io/docs/)!

For tutorials see the [tutorial page](http://deepstream.io/tutorials/)!

## Usage with Typescript

This repository comes with the Typescript typings bundled. No need to download them separately!

Make sure the `src/client.d.ts` file is accessible to the Typescript compiler. Do this by making sure it's an included file in tsconfig.json by adding a `typeRoots` defininition. (Required Typescript 2.0 or higher.)

>  "typeRoots": [
     "./node_modules/deepstream.io-client.js/src/client.d.ts"
    ]
