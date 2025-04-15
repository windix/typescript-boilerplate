# Typescript Boilerplate

## Setup

### gitignore

https://www.toptal.com/developers/gitignore/api/node

### Typescript

https://www.typescriptlang.org/download/

```sh
npm i -D typescript@latest
npm i -D tsx

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

- [recommended extenstions](./.vscode/extensions.json)
  - [dbaeumer.vscode-eslint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  - [EditorConfig.EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
  - [esbenp.prettier-vscode](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [default settings](./.vscode/settings.json)

### nvm / node

```sh
node --version > .nvmrc

npm i -D @types/node
npm i -D @tsconfig/node22

```

To let nvm use the right version:

```sh
nvm use

```

### nodemon

https://blog.logrocket.com/configuring-nodemon-typescript/

### copy

```sh
# backup destination files (e.g. package.json)
# replace dest/
# replace --dry-run when ready
rsync -av --dry-run --exclude=node_modules --exclude=dist --exclude=.git --exclude=README.md . dest/

```
