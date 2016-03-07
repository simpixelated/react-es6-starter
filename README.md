# react-es6-starter
Boilerplate React starter kit with ES 6/2015, ESLint, and Webpack.

Uses `npm` as a build script (interfacing with webpack, etc.). To see a list of commands: `npm run`.

### ESLint

This repo uses [ESLint](http://eslint.org/), with rules defined in .eslintrc. It includes best practices for ES6, React, and Lodash. `npm run lint` will check code.

There many [IDE integrations for ESLint](http://eslint.org/docs/user-guide/integrations), but the recommended one for Sublime Text is [SublimeLinter](http://www.sublimelinter.com/en/latest/) with the [eslint plugin](https://github.com/roadhump/SublimeLinter-eslint).

### Babel

This repo uses Babel to convert ES6/ES2015 code to ES5, which can be run in all browsers. It's converted via Webpack, either on the fly with a dev server (`npm start`), or during a build step (`npm run build`).

Hint: [ES6 syntax highlighting in Sublime Text 3](https://github.com/babel/babel-sublime).
