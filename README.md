jenius-cli
==========

CLI helper to interact with Jenius&#39; API

[![Version](https://img.shields.io/npm/v/jenius-cli.svg)](https://npmjs.org/package/jenius-cli)
[![CircleCI](https://circleci.com/gh/mathdroid/jenius-cli/tree/master.svg?style=shield)](https://circleci.com/gh/mathdroid/jenius-cli/tree/master)
[![Appveyor CI](https://ci.appveyor.com/api/projects/status/github/mathdroid/jenius-cli?branch=master&svg=true)](https://ci.appveyor.com/project/mathdroid/jenius-cli/branch/master)
[![Codecov](https://codecov.io/gh/mathdroid/jenius-cli/branch/master/graph/badge.svg)](https://codecov.io/gh/mathdroid/jenius-cli)
[![Downloads/week](https://img.shields.io/npm/dw/jenius-cli.svg)](https://npmjs.org/package/jenius-cli)
[![License](https://img.shields.io/npm/l/jenius-cli.svg)](https://github.com/mathdroid/jenius-cli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g jenius-cli
$ jenius COMMAND
running command...
$ jenius (-v|--version|version)
jenius-cli/0.1.0 darwin-x64 node-v9.11.1
$ jenius --help [COMMAND]
USAGE
  $ jenius COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`jenius hello`](#jenius-hello)
* [`jenius help [COMMAND]`](#jenius-help-command)

## `jenius hello`

Describe the command here

```
USAGE
  $ jenius hello

OPTIONS
  -n, --name=name  name to print

DESCRIPTION
  Describe the command here
  ...
  Extra documentation goes here
```

_See code: [src/commands/hello.js](https://github.com/mathdroid/jenius-cli/blob/v0.1.0/src/commands/hello.js)_

## `jenius help [COMMAND]`

display help for jenius

```
USAGE
  $ jenius help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v1.2.11/src/commands/help.ts)_
<!-- commandsstop -->
