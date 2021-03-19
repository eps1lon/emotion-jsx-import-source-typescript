# jsxImortSource vs eslint-disable directives

Steps to reproduce:

1. clone this repository
1. `yarn`
1. `yarn start`


Expected: passes
Actual: fails (but passes when using `jsxImportSource` instead of `@jsxImportSource` in comments)