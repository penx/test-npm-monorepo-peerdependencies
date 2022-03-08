# npm peer dependency resolution

## To test

```sh
git clone https://github.com/penx/test-npm-monorepo-peerdependencies.git
cd test-npm-monorepo-peerdependencies
npm i
npm i typescript --workspace=package1
cat ./package1/package.json
```

## Result

```json
  "dependencies": {
    "package2": "1.0.0",
    "typescript": "^4.6.2"
  }
```