[![](docs/logo.png)](https://simulatedgreg.gitbooks.io/electron-vue/content/index.html)

> The boilerplate for making electron apps built with vue (pretty much what it sounds like).

[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)

[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com) [![forthebadge](http://forthebadge.com/images/badges/uses-js.svg)](http://forthebadge.com) [![forthebadge](http://forthebadge.com/images/badges/makes-people-smile.svg)](http://forthebadge.com)

## Overview
The aim of this project is to remove the need to setup electron apps using vue. Since vue can take advantage of module loaders like webpack, getting everything to play nicely can be a little tricky.

#### Check out the documentation [here](https://simulatedgreg.gitbooks.io/electron-vue/content/index.html).

Things you'll find in this boilerplate...
  * Basic project structure
  * Project scaffolding using [vue-cli](https://github.com/vuejs/vue-cli)
  * Ready to use Vue plugins ([vue-electron](https://github.com/SimulatedGREG/vue-electron),  [vue-resource](https://github.com/vuejs/vue-resource), [vue-router](https://github.com/vuejs/vue-router), [vuex](https://github.com/vuejs/vuex))*
  * Installed [vue-devtools](https://github.com/vuejs/vue-devtools) and [devtron](https://github.com/electron/devtron) tools for development
  * Ability to easily package your electron app using [electron-packager](https://github.com/electron-userland/electron-packager)
  * Handy NPM scripts
  * Use of [webpack](https://github.com/webpack/webpack) and [vue-loader](https://github.com/vuejs/vue-loader) for Hot Module Replacement
  * HTML/CSS/JS pre-processor support with [vue-loader](https://github.com/vuejs/vue-loader/)
  * ES6 by default
  * ESLint (extends 'standard')*

\*Customizable during vue-cli scaffolding

### Getting Started
This boilerplate was built as a template for [vue-cli](https://github.com/vuejs/vue-cli) and includes options to customize your final scaffolded app.
```bash
# Install vue-cli and scaffold boilerplate
npm install -g vue-cli
vue init simulatedgreg/electron-vue my-project

# Install dependencies and run your app
cd my-project
npm install
npm run dev
```

### Contributing
Wanting to submit a pull request? Make sure to read [this](docs/contributing.md) first.
