# Jam3 Open Source Library Generator

[![Greenkeeper badge](https://badges.greenkeeper.io/Jam3/nyg-opensource-jam3.svg)](https://greenkeeper.io/)
[![stable](http://hughsk.github.io/stability-badges/dist/stable.svg)](http://github.com/hughsk/stability-badges)

Jam3 Open Source Library Generator with no build configuration and no prompts

* [Usage](#usage)
* [Main scripts](#main-scripts) – Running scripts

## Usage

[![NPM](https://nodei.co/npm/nyg-opensource-jam3.png)](https://www.npmjs.com/package/nyg-opensource-jam3)

`nyg-opensource-jam3` is using [nyg](https://github.com/Jam3/nyg) to generate the template, and should be installed first.

```bash
npm i nyg -g
npm i nyg-opensource-jam3 -g
cd your-project-directory
nyg nyg-opensource-jam3
```

## Contribute

### Structure

#### Contribute with boilerplate

1.  Go to `/templates`
2.  Run `npm i`
3.  Ready to go, everything is inside that folder

#### Contribute with the generator

1.  Review `/index.js`, everything is there

### Boilerplate main scripts

In the template, you can run:

#### `npm test`

Runs the test watcher in an interactive mode

#### `npm run test-ci`

It runs a set of tasks previous to `git push` and in the Continues Integration service before merging.

The tasks are:
- Unit tests
- Linters
- Bundle size checking
- Dependencies vulnerability audit

## Recommended Services

It's recommended to integrate the below services:
1. [Snyk](https://snyk.io/)
2. [Travis CI](https://travis-ci.org/)
3. [Greenkeeper](https://greenkeeper.io/)
4. [Coveralls](https://coveralls.io/)
5. [David-dm](https://david-dm.org/)
6. [Code Climate](https://codeclimate.com)
7. [Sonar cloud](https://sonarcloud.io/)
8. [Bundle Size](https://github.com/siddharthkp/bundlesize) It's already include, but not integrated with the status in GitHub

After you start using the services you can move forward and add the badges in your Readme, to learn more use [https://shields.io/](https://shields.io/)
