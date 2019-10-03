# Stackbit Fjord Theme

This site was generated by [www.stackbit.com](https://www.stackbit.com), v0.2.73.

# Running Your Site Locally

1. Install [Node.js and npm](https://nodejs.org/en/)

1. Install npm dependencies:

        npm install

1. get "stackbit-api-key" from project menu in [Stackbit dashboard](https://app.stackbit.com/dashboard)

1. run the following command to assign this key to `STACKBIT_API_KEY` environment variable:

        export STACKBIT_API_KEY={stackbit_netlify_api_key}

1. run the following command to fetch additional site contents from Stackbit if needed:

        npx @stackbit/stackbit-pull --stackbit-pull-api-url=https://b9e3716f.ngrok.io/pull/5d9592857b99ac8f2f80a780

1. Starts a development server

        npm run develop

1. Browse to [http://localhost:8000/](http://localhost:8000/)