# Search.

  "ack"-inspired grep-ish search utility written with nodejs.

## Installation

     $ npm install -g search

## Usage

```bash

Usage: search [options] <query> [path ...]

Options:

  -h, --help     output usage information
  -v, --version  output the version number
  -H, --hidden   search hidden files and directories

```

## Examples

  The given `<query>` is a case-insensitive regular express,
  so the query may express simple words or phrases, as well
  as ones like `foo(bar)?`.