This example demonstrates how to use [Express](http://expressjs.com/) 4.x and
[Passport](http://passportjs.org/) to authenticate users using Google.

## Instructions

To install this example on your computer, clone the repository and install
dependencies.

```bash
$ git clone git@github.com:cfvelasquez095/OAuth2.0-Google-Sample.git
$ cd OAuth2.0-Google-Sample
$ npm install
```

The example uses environment variables to configure the consumer key and
consumer secret needed to access Google's API.  Start the server with those
variables set to the appropriate credentials.

```bash
$ CLIENT_ID=__GOOGLE_CLIENT_ID__ CLIENT_SECRET=__GOOGLE_CLIENT_SECRET__ node server.js
```

Open a web browser and navigate to [http://localhost:3000/](http://localhost:3000/)
to see the example in action.
