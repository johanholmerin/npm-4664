package.json contains incompatible versions of eslint and eslint-plugin-import,
which have been installed using `npm install --force`

`npm ci` works on 8.5.5 but fails on 8.6.0

Caused by https://github.com/npm/cli/commit/bd96ae4071f9cc8a65e741f414db12e98537971d
