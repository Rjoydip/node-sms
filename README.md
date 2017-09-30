# node-sms

> Send sms using node.js and twilio 

## Running Locally

```bash
$ git clone https://github.com/Rjoydip/node-sms.git # or clone your own fork
$ cd node-sms
$ npm install
$ npm start
```

Your app should now be running on [localhost:3000](http://localhost:3000).

## Server API

### `app.get('/');`

Render index.html

### `app.get('/send');`

Send sms messageing with dummy twilio number.

#### `Response:`

* 200: Success. Payload: `message.sid`.
* 422: Error. Payload: error object.
