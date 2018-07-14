# vue-sassy-taiwind

> A vue.js boilerplate that uses sass and tailwindcss

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080 (one terminal tab)
npm run dev
npm run build:sass && npm run compile:tailwind # in another terminal window

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```


## Sytax Highlighting Issues

To have  vscode stop complaining about the @apply rule, install the PostCss syntax plugin and copy and paste the following code into your vscode settings.

```json
"files.associations": {
    "*.scss": "postcss"
},
"emmet.includeLanguages":{
    "postcss": "css"
},
"emmet.syntaxProfiles": {
    "postcss": "css"
}
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
