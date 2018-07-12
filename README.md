Repository to reproduce [lein-cljsbuild issue 431](https://github.com/emezeske/lein-cljsbuild/issues/431).

When trying to compile with

```
lein cljsbuild once
```

you will get the following warning:

```
WARNING: Use of undeclared Var cljsbuild-431.core/random-uuid at line 5 src/cljsbuild_431/core.cljs
```
