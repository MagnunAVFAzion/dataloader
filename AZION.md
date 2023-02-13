# Azion Dataloader
Package version to run in Azion Cells (edge runtime).

## Build
```
yarn install
yarn pack:azion
```
Now you can use `dataloader-azion-2.1.0.tgz` file in package.json.
Ex.:
```
  "dependencies": {
    ...
    "dataloader-azion": "file:PATH_TO_FILE_DIR/dataloader-azion-2.1.0.tgz"
    ...
  },
```

## Publish pkg in github
```
npm login --scope=@NAMESPACE --auth-type=legacy --registry=https://npm.pkg.github.com
npm publish
```