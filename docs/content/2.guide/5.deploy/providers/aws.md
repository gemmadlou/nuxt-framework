---
icon: IconCloud
---

# AWS

How to deploy Nuxt to [AWS Lambda](https://aws.amazon.com/lambda/)

## Deployment presets

You can use the Nuxt config to explicitly set the preset:

```js [nuxt.config.js|ts]
xport default defineNuxtConfig({
    nitro: {
        preset: 'aws-lambda',
        serveStatic: true
    }
})
```

Or directly use the NITRO_PRESET environment variable when running nuxt build:

```sh
NITRO_PRESET=aws-lambda nuxt build
```

🔎 Check the Nitro deployment for all possible deployment presets and providers.

## Learn more

:ReadMore{link="https://nitro.unjs.io/deploy/providers/aws.html" title="the Nitro documentation for AWS deployment"}
