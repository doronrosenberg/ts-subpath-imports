# Typescript and Subpath Imports

Run tsc and you get:

```
> ts-subpath-imports@1.0.0 build
> tsc

src/test.ts:1:21 - error TS2307: Cannot find module '#internal/foo' or its corresponding type declarations.

1 import { foo } from "#internal/foo";
                      ~~~~~~~~~~~~~~~

src/test.ts:2:21 - error TS2307: Cannot find module '#internal2' or its corresponding type declarations.

2 import { bar } from "#internal2";
                      ~~~~~~~~~~~~


Found 2 errors in the same file, starting at: src/test.ts:1


Process finished with exit code 2
```