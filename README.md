# Parcel & Svelte & am-mocktimes Starter kit

## Change Parcel to Vite

https://github.com/ampcpmgp/vite-svelte-mocktimes-starter

## Setup

```shell
npm install -g degit
npx degit ampcpmgp/parcel-svelte-mocktimes-starter
npm i
```

* edit `package.json` `name` property
* edit `README.md`
* edit `src/index.html` title

## Start

```shell
npm start # Open http://localhost:1234/patterns.html
npm run storybook
```

## Test

```shell
npm test
# or watch mode
npm run test:watch
# or watch spefied test name
npx ava --match 'composite/example' --watch
```

## Lint

```shell
npm run lint
```

or vscode extensions <https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint>

## Code Format

```shell
npm run format
```

or vscode extensions <https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode>

### Generate parts template

```shell
npx am-parts -n __NAME__
```
