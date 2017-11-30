# 01-basic


```bash
./node_modules/.bin/webpack src/index.js dist/bundle.js
```


### Using a configuration

```bash
./node_modules/.bin/webpack --config webpack.config.js
```

### npm script
```bash
npm run build -- --colors
```

> Note that within scripts we can reference locally installed npm packages by name instead of writing out the entire path. 

在script中，`webpack`与`./node_modules/.bin/webpack`等效。