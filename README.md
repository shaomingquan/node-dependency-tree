### dependency-tree-alias-hack

global alias support for [dependency-tree](https://www.npmjs.com/package/dependency-tree).

```
// global alias
global.__alias = {
    '@server': '/user/smq/2017/server/'
}
```
then we use the alias (supported by [module-alias](https://www.npmjs.com/package/module-alias)).
```
var index = require('@server/index');
```

now it can also resolve the deps well.

******

because it is an ugly modify, so I fork the package. 侵删(delete if forbid).
