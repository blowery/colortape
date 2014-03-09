# colortape

Colorize test results of [tape](https://github.com/substack/tape).

[![NPM version](https://badge.fury.io/js/colortape.png)](http://badge.fury.io/js/colortape)

## Usage

Pipe the result of `tape` command.

```sh
tape test/foo.js | colortape
```

To use with `npm test`, configure your `package.json`.

```json
{
  "scripts": {
    "test": "tape test/**/*.js | colortape"
  }
}
```
