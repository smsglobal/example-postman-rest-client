# SMSGlobal Postman Collection

The Postman App allows you to test API's quickly and easily.

Download our Postman collection (v2.1) for SMSGlobal API.

Includes the following API endpoints:

* [HTTP API](https://www.smsglobal.com/http-api/)
* [REST API](https://www.smsglobal.com/rest-api/)
* [SOAP API](https://www.smsglobal.com/soap-api/)
* [OTP API](https://www.smsglobal.com/otp-api/)
* [WhatsApp API](https://www.smsglobal.com/whatsapp-api/)

View the API documentation [here](https://www.smsglobal.com/api-reference/)

## Installation

Find the Postman App [here](https://www.postman.com/)

The Collection will provide quick access to our range of APIs.

The Environment file will provide you the environment variables needed to test the Collection.

[Download SMSGlobal Postman Collection](collection.json)

[Download SMSGlobal Environment variables](environment.json)


## Setup

### Import

On the Postman App, select `Import`, to import the `collection.json` file and the `environment.json` file.

### Grab your relevant API access keys.

Login to your SMSGlobal MXT account [here](https://mxt.smsglobal.com/integrations)

Depending on the API you wish to test, there are 2 sets of credentials you may need.

#### Master API Key Credentials

You'll need these credentials for testing the `HTTP API` and the `SOAP API`.

Copy your `username` and `password` values.

Save them into your Postman Environment variables `AccountUsername` and `AccountPassword` respectively.

#### REST API Credentials

You'll need these credentials for testing the `REST API` and the `OTP API`.

Copy your `Key` and `Secret` values.

Save them into your Postman Environment variables `RestApiKey` and `RestApiSecret` respectively.

### Environment Variables

You should now have all the environment variables set and ready to test.

Note there are 2 environment variables populated dynamically via Postman pre-request/post-response scripts.

These will handle API authentication for you, and you won't need to manually place authentication tokens into each request.

`authorization` - This is used in the `REST API` and `OTP API`

`SoapApiTicket` - This is used in the `SOAP API`


## Testing

Ensure the environment is selected in your Postman App.

Each request will need to be populated with the relevant information. Find out more about each parameter in the [API docs](https://www.smsglobal.com/api-reference/)

Remove any optional filters or request parameters that are not required for the request.
