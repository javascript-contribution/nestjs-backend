

<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

  <p align="center">A progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications.</p>
    <p align="center">
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/v/@nestjs/core.svg" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/dm/@nestjs/common.svg" alt="NPM Downloads" /></a>
<a href="https://circleci.com/gh/nestjs/nest" target="_blank"><img src="https://img.shields.io/circleci/build/github/nestjs/nest/master" alt="CircleCI" /></a>
<a href="https://coveralls.io/github/nestjs/nest?branch=master" target="_blank"><img src="https://coveralls.io/repos/github/nestjs/nest/badge.svg?branch=master#9" alt="Coverage" /></a>
<a href="https://discord.gg/G7Qnnhy" target="_blank"><img src="https://img.shields.io/badge/discord-online-brightgreen.svg" alt="Discord"/></a>
<a href="https://opencollective.com/nest#backer" target="_blank"><img src="https://opencollective.com/nest/backers/badge.svg" alt="Backers on Open Collective" /></a>
<a href="https://opencollective.com/nest#sponsor" target="_blank"><img src="https://opencollective.com/nest/sponsors/badge.svg" alt="Sponsors on Open Collective" /></a>
  <a href="https://paypal.me/kamilmysliwiec" target="_blank"><img src="https://img.shields.io/badge/Donate-PayPal-ff3f59.svg"/></a>
    <a href="https://opencollective.com/nest#sponsor"  target="_blank"><img src="https://img.shields.io/badge/Support%20us-Open%20Collective-41B883.svg" alt="Support us"></a>
  <a href="https://twitter.com/nestframework" target="_blank"><img src="https://img.shields.io/twitter/follow/nestframework.svg?style=social&label=Follow"></a>
</p>
  <!--[![Backers on Open Collective](https://opencollective.com/nest/backers/badge.svg)](https://opencollective.com/nest#backer)
  [![Sponsors on Open Collective](https://opencollective.com/nest/sponsors/badge.svg)](https://opencollective.com/nest#sponsor)-->


## Description
[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.
## node-nestjs-backend

node-nestjs-backen will have api for all javascript users and contributors. Anyone who wants to refer the work or code for their future projects, can do that by just cloning or downloading zip files. This will be shared work with all contributors. Github could be used as a common platform for depositing individual’s valuable input on any framework or mostly into js dependencies libraries.

## Branch structure

Never push changes to the master branch always check-out a branch and raise a PR.

Create a feature branch from development branch(master or main in our case)

Feature branch should only contain the work for only one feature It should not have multiple features in it Feature branch name should be in format (-) e.g. NEST-signIn e.g. NEST-file-upload Write code in feature branch only

Before raising a PR, make sure you run local tests on your machine using npm run test or any other script to run your tests.

Put reviewers on your PR. Squash and merge commits from the Github UI.

While sending review, make sure your branch has latest code from development branch so that we don't get conflicts.

update development branch from server, merge it to your feature branch and create PR git merge --no-ff master Push only stable code in repo

Bugs related to a feature should be fixed in that branch

Commit Messages Format:

Add/feat = Create a capability e.g. feature, test, dependency.

Cut = Remove a capability e.g. feature, test, dependency.

Fix = Fix an issue e.g. bug, typo, accident, misstatement.

Bump = Increase the version of something e.g. dependency.

Make = Change the build process, or tooling, or infra.

Start = Begin doing something; e.g. create a feature flag.

Stop = End doing something; e.g. remove a feature flag.

Refactor = A code change that MUST be just a refactoring.

Reformat = Refactor of formatting, e.g. omit whitespace.

Optimize = Refactor of performance, e.g. speed up code.

Document = Refactor of documentation, e.g. help files.
## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## Stay in touch

- Author - [Kamil Myśliwiec](https://kamilmysliwiec.com)
- Website - [https://nestjs.com](https://nestjs.com/)
- Twitter - [@nestframework](https://twitter.com/nestframework)

## License

Nest is [MIT licensed](LICENSE).


