# Stackbit Ampersand Theme

This site was generated by [www.stackbit.com](https://www.stackbit.com), v0.2.79.

Stackbit Ampersand Theme original README is located [here](./README.theme.md).

The content of this site is managed by Contentful. Visit [https://app.contentful.com/spaces/akq82pz4lj5t](https://app.contentful.com/spaces/akq82pz4lj5t) to manage site content.

# Running Your Site Locally

1. Install [Node.js and npm](https://nodejs.org/en/)

1. Install npm dependencies:

        npm install

1. get "stackbit-api-key" from project menu in [Stackbit dashboard](https://app.stackbit.com/dashboard)

1. run the following command to assign this key to `STACKBIT_API_KEY` environment variable:

        export STACKBIT_API_KEY={stackbit_netlify_api_key}

1. run the following command to fetch site contents from Contentful:

        npx @stackbit/stackbit-pull --stackbit-pull-api-url=https://api.stackbit.com/pull/5dc0821d82692d0013d1df1d

1. Starts a development server

        npm run develop

1. Browse to [http://localhost:8000/](http://localhost:8000/)
