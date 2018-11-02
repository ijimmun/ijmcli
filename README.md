ijmcli
======

Testing oclif as package

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/ijmcli.svg)](https://npmjs.org/package/ijmcli)
[![Downloads/week](https://img.shields.io/npm/dw/ijmcli.svg)](https://npmjs.org/package/ijmcli)
[![License](https://img.shields.io/npm/l/ijmcli.svg)](https://github.com/ijimmun/ijmcli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g ijmcli
$ ijmcli COMMAND
running command...
$ ijmcli (-v|--version|version)
ijmcli/0.0.0 win32-x64 node-v8.11.2
$ ijmcli --help [COMMAND]
USAGE
  $ ijmcli COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`ijmcli hello [FILE]`](#ijmcli-hello-file)
* [`ijmcli help [COMMAND]`](#ijmcli-help-command)

## `ijmcli hello [FILE]`

describe the command here

```
USAGE
  $ ijmcli hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ ijmcli hello
  hello world from ./src/hello.ts!
```

_See code: [src\commands\hello.ts](https://github.com/ijimmun/ijmcli/blob/v0.0.0/src\commands\hello.ts)_

## `ijmcli help [COMMAND]`

display help for ijmcli

```
USAGE
  $ ijmcli help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.1.3/src\commands\help.ts)_
<!-- commandsstop -->
