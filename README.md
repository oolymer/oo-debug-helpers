# oo-debug-helpers

[![Travis Build](https://img.shields.io/travis/oolymer/oo-debug-helpers/master.svg)](https://travis-ci.org/oolymer/oo-debug-helpers)
[![MIT License](https://img.shields.io/badge/license-MIT%20License-blue.svg?style=flat)](https://opensource.org/licenses/MIT)
[![Polymer 2](https://img.shields.io/badge/webcomponents-Polymer%202-orange.svg?style=flat)](https://www.polymer-project.org/2.0/start/)

> A dashboard that helps to debug our applications.

**Table of Contents:**

<!-- TOC depthFrom:2 -->

- [Usage](#usage)
- [Contributing](#contributing)

<!-- /TOC -->

## Usage

Add `oo-debug-helpers` as dependency to your `bower.json`.

~~~json
{
  "dependencies": {
    "oo-debug-helpers": "oolymer/oo-debug-helpers#0.1.0"
  }
}
~~~

Add `oo-hud.html` to your `*.html`.

~~~html
<link rel="import" href="../../oo-debug-helpers/oo-hud.html">
~~~

Use `<oo-hud>` element.

~~~html
<body>
  <oo-hud></oo-hud>
</body>
~~~

## Contributing

Install `npm` and `bower` dependencies.

~~~
$ npm install
$ npm run install:bower
~~~

Start the development server and open the default browser.

~~~
$ npm start
~~~

Run test suites in headless browsers.

~~~
$ npm test
~~~

Update the change log.

~~~
$ github_changelog_generator oolymer/oo-debug-helpers --simple-list --no-issues --output CHANGES.md --header-label "# CHANGES" --future-release v0.1.0
~~~
