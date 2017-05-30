# Installation

[![Greenkeeper badge](https://badges.greenkeeper.io/clayne11/jest-projects-repro.svg)](https://greenkeeper.io/)

`yarn run bootstrap`

# Tests

Running `yarn test` should run tests in both packages. It actually fails to
resolve the `tsconfig.json` file.

If you go into each package individually and run `yarn test`, they will work.
