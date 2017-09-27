# angular-modular-showcase

Simple showcase how a modular angular app can be built. Each app is runnable on it's own as each contains a standalone entry point.

However the submodules are designed to be included in the main-module. Each submodule is included via a lazy-loaded route.

## Module A

Module A contains the setup for angular playground, a UI specific framework that enables to test and develop visual components fast and reliable. A similar technology would be Storybook for ReactJS.

## Project layout

You may notice that the root folder contains the folder 'packages/node_modules'. This is to utilize the way how node resolves modules in order to use just one repository and a flat project structure. Please [this explanation] by PouchDB for the reasons.

[this explanation]: [https://gist.github.com/nolanlawson/457cdb309c9ec5b39f0d420266a9faa4]