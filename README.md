# reproduce-volar_update_import_dont_work


## Description

Update imports on file move not working.

## Env info

- volar: v0.40.13
- vscode: 1.71.2

## Project Setup

```sh
pnpm i
```

## Steps to reproduce

1. disable all extensions except volar
2. move `src/components/HelloWorld.vue` to `src/HelloWorld.vue`
3. checkout [App.vue](./src/App.vue), the import remain the same.