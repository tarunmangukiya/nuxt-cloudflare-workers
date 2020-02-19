# NuxtJS on Cloudflare Workers

Find full article on how to deploy NuxtJS on Cloudflare at https://scotch.io/tutorials/deploying-a-static-nuxtjs-site-to-cloudflare-workers

## Build Setup

``` bash
# install dependencies
$ npm run install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).

## Publish to Cloudflare workers

Change `account_id` in `wrangler.toml` to your Cloudflare account id.

``` bash
# generate static project & publish it to Cloudflare Workers
$ npm run publish
```
