# NPM Command line options

https://docs.npmjs.com/cli-documentation/

## Install a package globally

```
npm --global install yarn
```

## Save a package in `package.json`as a dependency

```
npm --save install underscore
```

Normal dependencies are required for runtime.

## Save a package in `package.json` as a dev dependency

```
npm install --save-dev jest-puppeteer puppeteer jest
```

Dev dependencies are not required for runtime.

