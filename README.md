# Pay Global Platform APIs OpenAPI Specification
[![Build Status](https://travis-ci.com/payglobal/platform-api-docs.github.io.svg?branch=master)](https://travis-ci.org/payglobal/platform-api-docs.github.io)

## Links

- [Reference Documentation](https://docs.api.payglobal.me/platform-api-docs.github.io/)
- OpenAPI Raw Files: [JSON](https://docs.api.payglobal.me/openapi.json) [YAML](https://docs.api.payglobal.me/openapi.yaml)

## Working on specification
### Install

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and run `npm install` in the repo root

### Usage

#### `npm start`
Starts the development server.

#### `npm run build`
Bundles the spec and prepares web_deploy folder with static assets.

#### `npm test`
Validates the spec.

#### `npm run gh-pages`
Deploys docs to GitHub Pages. You don't need to run it manually if you have Travis CI configured.
