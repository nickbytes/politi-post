app for sending postcard to your rep and senators. using lob and stripe.

built using next.js

clone the repo then run

`npm install`
`npm run dev`

We're using next.js's directory based routing for now so our containers are in there and all the react bits that do the heavy lifting are in `./components`

also requires a `secret.js` file that exports and object with `'lobAPIKey'`