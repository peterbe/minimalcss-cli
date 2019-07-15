# minimalcss

[![Build Status](https://travis-ci.org/peterbe/minimalcss-cli.svg?branch=master)](https://travis-ci.org/peterbe/minimalcss-cli)
[![NPM version](https://img.shields.io/npm/v/minimalcss-cli.svg)](https://www.npmjs.com/package/minimalcss-cli)
[![styled with prettier](https://img.shields.io/badge/styled_with-prettier-ff69b4.svg)](#badge)
[![Renovate enabled](https://img.shields.io/badge/renovate-enabled-brightgreen.svg)](https://renovateapp.com/)

## Usage

Install:

```bash
yarn add minimalcss-cli --dev
```

You can install it globally if you like:

```bash
yarn global add minimalcss-cli
```

```bash
npm install [--save-dev|--global] minimalcss-cli
```

Now you can run it:

```bash
./node_modules/.bin/minimalcss https://example.com/ https://example.com/aboutus > minimal.min.css
```

## Help needed

Let's make this a thriving community project!

Help needed with features, tooling, and much testing in real web performance
optimization work.

## Development

First thing to get started, once you've cloned the repo is to install all
the dependencies:

```sh
yarn
```

### Testing

To run the tests:

```bash
yarn test
```

### Prettier

All code is expected to conform with [Prettier](https://prettier.io/) according
to the the `.prettierrc` file in the root of the project.

To check that all your code conforms, run:

```bash
yarn lintcheck
```

## License

Copyright (c) 2017-2018 [Peter Bengtsson](https://www.peterbe.com).
See the [LICENSE](/LICENSE) file for license rights and limitations (MIT).
