dotenv-exec
===========

This package provides `dotenv` command to run commands with [dotenv](https://github.com/motdotla/dotenv/).

Install
-------

```
$ npm install dotenv-exec
```

Usage
-----

Create a `.env` like

```
FOO=BAR
```

and run `dotenv` command like

```
$ dotenv node -e "console.log(process.env.FOO)"
BAR
```

Also you can specify a path to a configuration file with `-f` option like

```
$ dotenv -f /path/to/env node -e "console.log(process.env.FOO)"
```
