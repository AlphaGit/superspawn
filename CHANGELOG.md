# Changelog

## 0.1.0 — 2014-05-04
- Fix Windows issues: execute native commands, execute *.js files.
- You can pass a standard callback. Instead of returning a Q.promise the return will be `undefined`.
- Adds basic tests.

## 0.0.2 — 2014-04-28
- Remove stdout capture for stdio 'inherit'. It removed color from the output and broke Inquirer.js' 'checkbox' prompt. And it is not what the user expects anyway, even though it would be very nice to have.

## 0.0.1 — 2014-04-26
- Copy Apache Cordova coho's [superspawn.js](https://github.com/apache/cordova-coho/blob/c114399a7c6d03f805ffccf6b7ed74e2cb2c6b74/src/superspawn.js
).
- Add npm/node module stuff.
- Fix a stdio config bug.
- Replace shelljs(.which) with module 'which'.
