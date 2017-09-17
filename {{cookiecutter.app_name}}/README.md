# {{cookiecutter.app_name}}
>{cookiecutter.short_description}

## ToC

<!-- vim-markdown-toc GFM -->
* [Installing / Getting started](#installing--getting-started)
* [Developing](#developing)
  * [Built With](#built-with)
  * [Usage](#usage)
    * [Developing](#developing-1)
    * [Stylelinting](#stylelinting)
    * [Build](#build)
    * [Testing](#testing)
* [Versioning](#versioning)

<!-- vim-markdown-toc -->


## Installing / Getting started
First install all dependencies (js/elm) by running

```shell
npm run init
```

## Developing

### Built With

This project includes quite a few opinionated settings.
Therefore this template includes:

* Webpack as module bundler, dev server and build tool
* Babel for ES6
* StyleLint as scss/css linter
* CSS-Autoprefixing via postcss
* [SVG-Sprite](https://github.com/jkphl/svg-sprite) for automatic sprite/scss generation
* normalize.css as CSS-reset
* json-server + foreman to quickly build a fake API for rapid development


### Usage

#### Developing

```shell
npm start
```

This generates all necessary svg-sprite files (sprite + scss) and starts the
webpack-dev-server (`port:8080`) as well as the fake-api json-server (`port:8085`).

To only run the fake api server use

```shell
npm run api
```

or to just use the webpack-server run

```shell
npm run client
```


#### Stylelinting

While stylelint is also included in the webpack-dev-server you can also run
it separately via

```shell
npm run stylelint
```

or, if you want to automatically fix issues:

```shell
npm run stylelint:fix
```

#### Build

To create a production build including minification, run:

```shell
npm run build
```

This will output all files and bundles to a separate `dist/` directory.


#### Testing

**TODO**

## Versioning

We can maybe use [SemVer](http://semver.org/) for versioning. For the versions available, see the [link to tags on this repository](/tags).
