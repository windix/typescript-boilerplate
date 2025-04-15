# Typescript Boilerplate

## Setup

### gitignore

https://www.toptal.com/developers/gitignore/api/node

### Typescript

https://www.typescriptlang.org/download/

```sh
npm i -D typescript@latest

npx tsc --init --target esnext --module commonjs

```

```text
Created a new tsconfig.json with:
  target: esnext
  module: commonjs
  strict: true
  esModuleInterop: true
  skipLibCheck: true
  forceConsistentCasingInFileNames: true

You can learn more at https://aka.ms/tsconfig
```

### EditorConfig

https://editorconfig.org/

### ESLint / Typescript ESLint

https://eslint.org/docs/latest/use/getting-started

https://typescript-eslint.io/getting-started

```sh
npm init @eslint/config@latest

```

### prettier

https://prettier.io/docs/install

```sh
npm install --save-dev --save-exact prettier

node --eval "fs.writeFileSync('.prettierrc','{}\n')"

node --eval "fs.writeFileSync('.prettierignore','# Ignore artifacts:\nbuild\ncoverage\n')"

```

### vscode

### nvm / node
