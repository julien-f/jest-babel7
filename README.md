```
$ yarn
$ jest --no-cache
FAIL  ./index.spec.js
 ● Test suite failed to run

   TypeError: Cannot read property 'loose' of undefined (While processing preset: ".../jest-babel7/node_modules/babel-preset-env/lib/index.js")

     at _default (node_modules/babel-plugin-transform-es2015-modules-commonjs/lib/index.js:15:22)
         at Array.map (<anonymous>)
         at Array.map (<anonymous>)

Test Suites: 1 failed, 1 total
Tests:       0 total
Snapshots:   0 total
Time:        0.849s
Ran all test suites.
```
