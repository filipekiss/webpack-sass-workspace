My default workspace for working with Webpack and Sass (using Node Sass);

This is meant for applications where I want to keep the styles apart from the
scripts and so I avoid bundling them using webpack. A simple node-sass will
solve my issue, so that's what I'll use.

Included Batteries:

* [Webpack 4]
* [Sass] via [Node Sass]
* [XO]
* [Prettier] with a default config

I'll keep updating this project as I feel the need to.

## Basic Usage:

Put javascript in `src/scripts` and scss/sass in `src/styles`.

Things will be compiled to the `build` folder.

## Webpack config

* Webpack has an entry point configured to look at `src/scripts/index.js` and output is `dist/[name].[hash].js`
* The [WebpackManifestPlugin] is used to extract a `manifest.json` to the `dist` folder

filipekiss/2018 — [MIT]

[prettier]: https://prettier.io/
[webpack 4]: https://webpack.js.org/
[sass]: https://sass-lang.com/
[node sass]: https://github.com/sass/node-sass
[xo]: https://github.com/xojs/xo
[mit]: LICENSE.md
