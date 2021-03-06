# XCS - eXtremely awesome ECS CLI

**Work in progress**

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/xcs.svg)](https://npmjs.org/package/xcs)
[![Downloads/week](https://img.shields.io/npm/dw/xcs.svg)](https://npmjs.org/package/xcs)
[![License](https://img.shields.io/npm/l/xcs.svg)

[AWS Elastic Container Service](https://aws.amazon.com/ecs/) is Amazons managed docker container orchestration service.

This tool offers a intuitive cli for every day operations over ECS. The idea is to mirror ECS resource structure to the file system. As navigating the file system is a breeze, navigating clusters, services and other resource types becomes a breeze as well.

<!-- toc -->

- [XCS - eXtremely awesome ECS CLI](#xcs-e-xtremely-awesome-ecs-cli)
- [Usage](#usage)
- [Commands](#commands)
  <!-- tocstop -->

# Usage

<!-- usage -->

```sh-session
$ npm install -g xcs
$ xcs COMMAND
running command...
$ xcs (-v|--version|version)
xcs/0.0.0 linux-x64 node-v8.10.0
$ xcs --help [COMMAND]
USAGE
  $ xcs COMMAND
...
```

<!-- usagestop -->

# Commands

COMMANDS
autocomplete display autocomplete installation instructions
describe Describe current resource
help display help for xcs
init Mirror ECS state to current directory
update Update service
