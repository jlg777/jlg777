<hr>

<a name="top"></a>

[⬅️](../../README.md#head1234)

<p align="center">
  <img width="460" height="300" src="../assets/public/standardJS.svg">
</p>
<hr>

[JavaScript style](https://standardjs.com) guide, linter, and formatter.

```
$ npm install standard --global
$ npm install -D standard
```

## Inspeccionar y arreglar codigo

```
$ npx standard
$ standard "src/util/**/*.js" "test/**/*.js"

$ npx standard --fix
$ standard "src/util/**/*.js" "test/**/*.js" --fix

```

### package.json

```json
{
  "name": "my-cool-package",
  "devDependencies": {
    "standard": "*"
  },
  "scripts": {
    "test": "standard && node my-tests.js"
  }
}
```

[⬆️](#top)

<hr>
