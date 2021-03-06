Contribution Guide
===================

This document describes some points about contribution process for this project.
The project is being developed within community. Maintainer merges pull-requests, fixes critical bugs.

The maintainers of the project are:
- [Fernando Daciuk](https://github.com/fdaciuk)
- [Luan Muniz](https://github.com/luanmuniz)

## General notes

- In lieu of a formal styleguide, take care to maintain the existing coding style and please do follow [idiomatic.js](https://github.com/rwldrn/idiomatic.js)
- Add unit tests for any new or changed functionality.
- Lint and test your code using `npm test`.

And please:

### Always run `npm test` before sending a PR

## Sending Pull-Requests

If you fixed or added something useful to the project, you can send pull-request. It will be reviewed by maintainer and accepted, or commented for rework, or declined. If you a new and don't know what you should do to send a PR, please see [this tutorial](https://gist.github.com/luanmuniz/da0b8d2152c4877f93c4)

Before sending you Pull Request please don't forget to check your code with `npm test`. PR that don't pass tests will not be accept

## Scripts

### Development

- `npm run test:watch` - Run tests and watch all files

### Run once

- `npm run lint` - Check for lint errors on all files
- `npm run lint:fix` - Fix lint errors
- `npm test` - Run unit tests

### Deploy

- `npm version <version>` - Update project version
