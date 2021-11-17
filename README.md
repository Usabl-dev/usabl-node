# Usabl Survey Node.js Middleware (usabl-node)

Node.js SDK middleware that allows you to add surveys alongside your API responses. It logs incoming API calls, watching for actions that should trigger a Usabl survey. This SDK supports Express. This library is intended to be used on the server (it is not a client module).

## How to install

```shell
npm install --save usabl-nodejs
```

## Quickstart

The following shows how import Usabl for an example app using Express

### 1. Import the module:

```javascript
// 1. Import Modules
var express = require("express");
var app = express();
var usabl = require("usabl-nodejs");

// 2. Set the options, the only required field is applicationId.
var options = { applicationId: "<YOUR_TOKEN>" };

// 3. Initialize the middleware object with options
var usablMiddleware = moesif(options);

// 4b. Use the Usabl middleware to start showing surveys
app.use(usablMiddleware);
```

### 2. Enter Usabl Application Id

Your Usabl Application Id can be found in the [_Usabl Portal_](https://www.usabl.dev/).
After signing up for a Usabl account, your Usabl Application Id will be displayed during the onboarding steps.

You can always find your Usabl Application Id at any time by logging
into the [_Usabl Portal_](https://www.usabl.dev/), click on the top right menu,
and then clicking _Installation_.

```

## Configuration options

## Update a Single User

## Update a Single Company
```
