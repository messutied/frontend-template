# Frontend template

## Requirements

1. Node.js >= 8.7.0
1. Yarn

## Setup

Run the following commands under the project root folder:

1. `yarn install`
2. `yarn dev` to launch the development server.


## Production

Build the production ready bundle by running

```
yarn prod:build
```

The production bundle will be generated under the `dist` folder.


### Run production bundle in local machine

Need to install node http-server first with `npm i -g http-server`, then run:

```
yarn prod:start
```
