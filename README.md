# Elm-Webpack-Cookiecutter

This is an opionated cookiecutter to quickly scaffold Elm-Webpack projects.

## ToC

<!-- vim-markdown-toc GFM -->
* [Installing / Getting started](#installing--getting-started)
* [Developing](#developing)
  * [Built With](#built-with)
* [Versioning](#versioning)

<!-- vim-markdown-toc -->

## Installing / Getting started

To get started you first need to install Python and [Cookiecutter](https://cookiecutter.readthedocs.io/en/latest/installation.html), on your local maschine. Then you need to clone this repository.

Now just run the following command from the directory you ran
the `git clone` command in and cookiecutter will guide you trough a
minimal setup:

```shell
cookiecutter elm-webpack-cookiecutter
```

This will create a new project in its own directory and update certain files
according to the settings you made. This will also initialize a new git
repository inside the new directory. You can then add some central repository
 as a remote, make an initial commit and push the changes.


## Developing

### Built With

This project includes quite a few opinionated settings.
Therefore this template includes:

* Webpack as module bundler, dev server and build tool
* Babel for ES6
* StyleLint as scss/css linter
* CSS-Autoprefixing via postcss
* SVG-Sprite for automatic sprite/scss generation
* normalize.css as CSS-reset
* json-server + foreman to quickly build a fake API for rapid development


## Versioning

We  use [SemVer](http://semver.org/) for versioning.
