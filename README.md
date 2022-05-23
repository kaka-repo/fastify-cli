

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g fastify-cli
$ fastify COMMAND
running command...
$ fastify (--version)
fastify-cli/3.1.0 linux-x64 node-v18.2.0
$ fastify --help [COMMAND]
USAGE
  $ fastify COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`fastify generate`](#fastify-generate)
* [`fastify generate project [NAME]`](#fastify-generate-project-name)
* [`fastify help [COMMAND]`](#fastify-help-command)

## `fastify generate`

Generate fastify project

```
USAGE
  $ fastify generate

DESCRIPTION
  Generate fastify project
```

_See code: [dist/commands/generate/index.ts](https://github.com/fastify/fastify-cli/blob/v3.1.0/dist/commands/generate/index.ts)_

## `fastify generate project [NAME]`

Generate fastify project

```
USAGE
  $ fastify generate project [NAME] [--location <value>] [--overwrite] [--language <value>] [--lint <value>] [--test
    <value>] [--help]

ARGUMENTS
  NAME  Name of the project.

FLAGS
  --help              Show CLI help.
  --language=<value>  Programming Language you would like to use in this project.
  --lint=<value>      Lint Tools you would like to use in this project.
  --location=<value>  Location to place the project.
  --overwrite         Force to overwrite the project location when it exist.
  --test=<value>      Test Framework you would like to use in this project.

DESCRIPTION
  Generate fastify project
```

## `fastify help [COMMAND]`

Display help for fastify.

```
USAGE
  $ fastify help [COMMAND] [-n]

ARGUMENTS
  COMMAND  Command to show help for.

FLAGS
  -n, --nested-commands  Include all nested commands in the output.

DESCRIPTION
  Display help for fastify.
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v5.1.12/src/commands/help.ts)_
<!-- commandsstop -->
