# GitHub OAuth Device Flow Schema

This repository contains the OpenAPI schema file for using GitHub Device Flow authentication with ChatGPT Custom GPTs.

Any user who completes the login at github.com/login/device will be issued a device token.

## Working URL to Import in Custom GPT

Copy and paste the following URL into the "Import From URL" box in the GPT builder:

```
import url: https://ammonfife.github.io/gpt-github-oauth-device/.well-known/openapi.json
```

You can now use your personal OAuth client ID in a GPT action to access github.com.

