# NPM Command line options

https://docs.npmjs.com/cli-documentation/

## Install a package globally

```
npm --global install yarn
```

## Save a package in `package.json`as a dependency

```
npm install underscore
```

Normal dependencies are required for runtime.

## Save a package in `package.json` as a dev dependency

```
npm install --save-dev jest-puppeteer puppeteer jest
```

Dev dependencies are not required for runtime.

## nodemon
```
npm --global install nodemon
```
Start program with nodemon instead of mode and changes will be automatically applied.

## Publish app
```
npm login
```

```
npm publish
```

```
npm major|minor|patch
```

## link

Windows
```
type NUL > .npmignore
```

```
npm cache verify
```

In sub package called `wonder-lib`
```
npm link
```

In master package `bloggy`
```
npm link ../wonder-lib
```

## view

See repository connected to
```
npm view connect
```