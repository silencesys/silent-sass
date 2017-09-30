# Silent SASS

Is package containing helpful set of mixins and sass utilities to start
devloping responsive sites.

## Installation

```shell
npm install silent-sass
```

It is also recommended to install [laravel-mix](https://github.com/JeffreyWay/laravel-mix) or [webpack](https://github.com/webpack) and [sass-loader](https://github.com/webpack-contrib/sass-loader).
If you have installed __laravel-mix__ and __sass-loader__ webpack config file
should be modified to work with sass-loader:

```js
// your's webpack.mix.js file
mix.webpackConfig({
    module: {
        loaders: [{
            test: /\.scss$/,
            loader: 'style!css!sass'
        }]
    }
})
```

## SASS
It is recommended to set some default variables eg.
```scss

```
<!--
## Color naming
loud
very-pale
very-light
brilliant
light
neutral
moderate
dark
deep
nightfall
blackish
-->

## License
This package is licensed under the [MIT](license.md) license.