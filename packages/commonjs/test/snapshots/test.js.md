# Snapshot report for `test/test.js`

The actual snapshot is saved in `test.js.snap`.

Generated by [AVA](https://avajs.dev).

## can spread an object into module.exports

> Snapshot 1

    `'use strict';␊
    ␊
    const obj = {␊
      a: 'b',␊
      b: 'c'␊
    };␊
    ␊
    var main = {␊
      ...obj␊
    };␊
    ␊
    module.exports = main;␊
    `

## imports .cjs file extension by default

> Snapshot 1

    `'use strict';␊
    ␊
    var _export = {␊
      test: 42␊
    };␊
    ␊
    const { test } = _export;␊
    ␊
    console.log(test);␊
    ␊
    var main = {␊
    ␊
    };␊
    ␊
    module.exports = main;␊
    `