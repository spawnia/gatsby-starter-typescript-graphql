# gatsby-starter-typescript-graphql

This is a starter kit for [Gatsby.js](https://www.gatsbyjs.org/) websites written in TypeScript.
It leverages [GraphQL Code Generator](https://graphql-code-generator.com/) to enable typesafe GraphQL queries.

## Features

- Type safety with [TypeScript](https://www.typescriptlang.org/)
- Typesafe GraphQL with [graphql-codegen](https://graphql-code-generator.com/)
- Best practices with [ESLint](https://eslint.org/)
- Styling with [styled-components](https://styled-components.com/)

## Setup

Install the Gatsby CLI

```bash
yarn global add gatsby-cli
```

Create a new site

```bash
gatsby new <PROJECT_NAME> https://github.com/spawnia/gatsby-starter-typescript-graphql
```

By default, this starter adds the [GitHub GraphQL API](https://developer.github.com/v4/) as a source.
This can be quite useful for personal sites or blogs to show off your projects.

To connect with the GitHub API, you will need to add a personal access token to your environment:

```bash
cp .env.development.example .env.example
```

If you do not want to try this feature, remove `src/components/repositories.tsx` and its usages.

## Usage

Start a dev server

```bash
yarn start
```

Create a production build

```bash
yarn build
```

Serve the production build locally

```bash
yarn serve
```

Generate GraphQL type definitions

```bash
yarn codegen
```
