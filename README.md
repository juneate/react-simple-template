# Quick React Demo

A quick React demo and test. To run from the command line (in this root folder):

## 1. Install the Node Modules

```shell
npm install
```

## 2. Create empty `/src` folders, if they don't exist

```shell
mkdir -p src/components src/containers src/contexts src/pages src/utils src/css src/img
```

## 3. Run the Webpack test server

```shell
npm start
```

## 4. Build public files to `/dist`

Only required when publishing live online.

```shell
npm run build
```


## 5. Deploy to Netlify

Update the `siteId` property in [`.netlify/state.json`](.netlify/state.json). Then run the following:

```shell
npm run deploy
```
