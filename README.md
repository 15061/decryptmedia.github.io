# Website

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

## Installation

```console
npm install
```

## Local Development

```console
npm start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

## Build

```console
npm build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment

```console
GIT_USER=<Your GitHub username> DEPLOYMENT_BRANCH=gh-pages USE_SSH=true npm deploy
```

We're using GitHub pages to host this site, so make sure to set the deployment deploy to `gh-pages`, as above.