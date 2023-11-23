# Let's play a game

The goal is to compile project `packages/x` and include `foo` from `packages/internals` in the output so `packages/x` can be publish on npm without `packages/internals`.
There are rules:

- No use of rollup, pure TypeScript
- IF POSSIBLE, no relative paths for the import because it sort of defeats the purpose of having a monorepo here.
