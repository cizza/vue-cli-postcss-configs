# Multiple PostsCss configs in Vue-cli issue

This repo describes an issue I have with PostCss in vue-cli when using multiple postcss.config.js.
The postcss-loader Config Cascade doesn't seem to work.
The test subject in this case is a tailwindcss implementation, which is not being picked up by postcss-loader, if the postcss.config.js file is not in root of the project.

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
