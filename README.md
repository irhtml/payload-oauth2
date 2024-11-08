# Payload OAuth2 Plugin

<a href="LICENSE">
  <img src="https://img.shields.io/badge/license-MIT-brightgreen.svg" alt="Software License" />
</a>
<a href="https://github.com/wilsonle/payload-oauth2/issues">
  <img src="https://img.shields.io/github/issues/wilsonle/payload-oauth2.svg" alt="Issues" />
</a>
<a href="https://npmjs.org/package/payload-oauth2">
  <img src="https://img.shields.io/npm/v/payload-oauth2.svg?style=flat-squar" alt="NPM" />
</a>

# Features

- ✅ Compatible with Payload v3
- 🔐 Configures OAuth2 with any providers
- ✨ Zero dependencies
- ⚙ Highly customizable

# Integrations

Technically this plugin should work with all generic OAuth2 providers. Here are the list of providers that have been tested:

| Provider | Status                                                                                                                                                                                                   | Example                        |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------ |
| Google   | [![Test Google OAuth](https://github.com/WilsonLe/payload-oauth2/actions/workflows/test-google-oauth.yml/badge.svg)](https://github.com/WilsonLe/payload-oauth2/actions/workflows/test-google-oauth.yml) | [Config](./examples/google.md) |

# Installation

```
npm install payload-oauth2
yarn install payload-oauth2
pnpm install payload-oauth2
```

# Contributing

Contributions and feedback are very welcome.

To get it running:

1. Clone the project.
2. `pnpm install`
3. `pnpm dev`

# License

The MIT License (MIT). Please see [License File](LICENSE) for more information.

# Credits

This package was inspired by [Payload Plugin OAuth](https://github.com/thgh/payload-plugin-oauth).
