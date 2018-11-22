yarn/npm install

yarn test

> TypeError: Cannot read property 'info' of undefined

Because it requires webpack-log imports `ansi-colors` from `./node_modules/ansi-colors` not from `./node_modules/webpack-log/node_modules/ansi-colors`
