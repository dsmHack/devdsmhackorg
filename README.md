# Stackbit Fresh Theme

This site was generated by [www.stackbit.com](https://www.stackbit.com), v0.2.80.

Stackbit Fresh Theme original README is located [here](./README.theme.md).

The content of this site is managed by Forestry. Visit [https://forestry.io](https://forestry.io) to manage site content.

# Running Your Site Locally

1. [Install Hugo](https://gohugo.io/getting-started/quick-start/#step-1-install-hugo)

1. get "stackbit-api-key" from project menu in [Stackbit dashboard](https://app.stackbit.com/dashboard)

1. run the following command to assign this key to `STACKBIT_API_KEY` environment variable:

        export STACKBIT_API_KEY={stackbit_netlify_api_key}

1. run the following command to fetch additional site contents from Stackbit if needed:

        npx @stackbit/stackbit-pull --stackbit-pull-api-url=https://api.stackbit.com/pull/5df9920153e5ef0019599e25

1. Build the site and start the Hugo server with drafts enabled

        hugo server -D

1. Browse to [http://localhost:1313/](http://localhost:1313/)
