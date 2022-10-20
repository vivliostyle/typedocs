# typedocs
Vivliostyle source code documentation with typedoc

## Vivliostyle.js Core

- Source: https://github.com/vivliostyle/vivliostyle.js/tree/master/packages/core
- Typedoc: https://vivliostyle.github.io/typedocs/core/

### Making

TODO: This should be included in the CI of vivliostyle.js, but currenly making it manually:

```
$ cd vivliostyle.js/packages/core/
$ typedoc --out ../../../typedocs/core --entryPointStrategy expand ./src/vivliostyle
$ cd ../../../typedocs
$ git add .
$ git commit -m 'update core/'
```

## More...

TODO: add other Vivliostyle products
