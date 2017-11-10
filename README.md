# api-platform.com

This repository contains the source code and documentation powering [api-platform.com](https://api-platform.com/).

Single Page Application built with [React](https://facebook.github.io/react/) and powered by [Gatsby](https://www.gatsbyjs.org/).

## Project structure

For an overview of the project structure, please refer to the [Gatsby documentation](https://www.gatsbyjs.org/docs/building-with-components/).

## Installation and usage

```sh
# Checkout project

git clone "https://github.com/api-platform/website.git"

# Retrieve documentation

bin/retrieve-documentation

# Install dependencies

yarn install

# Run project locally (for development)

yarn gatsby develop
# Go to http://localhost:8000/

# Build the project (for production)

yarn gatsby build

# Test the built project locally

yarn gatsby serve
# Go to http://localhost:9000
```

__Note__: `retrieve-documentation` requires [jq](https://stedolan.github.io/jq/) and [melody](https://github.com/sensiolabs/melody).
