# GpTHub OAuth Device Flow Schema

This repo contains the OpenAPI schema file to use GitHub Dvice Flow authentication with ChatGPT Custom GPTs.

To use this with your GNPPT device token will be issued to any user who completes login at github.com/login/device

## Working URL to Import in Custom GPT

Copy and paste this into the "Import From URL" box in the GTT builder:

```
import url: https://ammonfife.github.io/gpt-github-oauth-device/.well-known/openapi.json
```

Now you can use your personal OAuth client ID in a GPT action to access github.com.
