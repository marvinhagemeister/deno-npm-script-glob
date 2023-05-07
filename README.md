# Deno missing glob support in npm scripts

Globs are not supported in npm scripts at the time of this writing in deno.

## Steps to reproduce

1. Clone this repo
2. Run `deno task test`

## Error

```sh
error: Error parsing script 'test'.

Caused by:
    Globs are currently not supported, but will be soon.
      *.test.js
      ~
```
