# 1.0.0-beta.2

## Other Changes

- Removing `api-check` on webpack config to make everything more flexible.

# 1.0.0-beta.1

## Bug Fixes

- Fixed issue where npm ignore was ignoring everything that this library should include.

# 1.0.0-beta.0

## Features

- Support a bunch of common files to be linked using symbolic link:
  - .editorconfig
  - .eslintignore
  - .gitignore
  - .npmignore
  - .travis.yml
  - LICENSE
- Support two code-check scripts (which should actually probably be eslint plugins...
  - console-check.js
  - only-check.js
- Support `.eslintrc` which should be extended using `extends`
- Support `karma.conf.js` with override option available via `kcdCommon.karma` property in `package.json`
- Support `webpack.config.js` with override option available via `kcdCommon.webpack` property in `package.json`