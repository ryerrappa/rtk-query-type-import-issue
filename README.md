# RTK Query type import issue

## Description
> please run `tsc` to see the relevant error.

Receive error:

```
 Cannot find module '@reduxjs/toolkit/dist/query/react/buildHooks'
```

when attempting to import type `MutationTrigger` in [src/App.tsx](./src/App.tsx).

## Context
- @reduxjs/tookit 2.0.1
- Vite 5.0.0
- Typescript 5.2.2
- tsconfig moduleResolution "bundler"
