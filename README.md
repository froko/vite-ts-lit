# vite-ts-lit

A project template for vite-based TypeScript projects with WebComponent support.
This template is intended to be used with [degit](https://github.com/Rich-Harris/degit#readme).

## Contents

- [vite](https://vitejs.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Lit](https://lit.dev/)
- [Prettier](https://prettier.io/)
- [ESLint](https://eslint.org/)
- [Husky](https://typicode.github.io/husky/#/)

## Installation Procedure

- Install [degit](https://github.com/Rich-Harris/degit#readme): `npm install -g degit`
- Create a new project directory: `mkdir my-vite-ts-lit-project`

  Please note: `degit` won't create a directory for you.

- Change into project directory: `cd my-vite-ts-lit-project`
- Download template files: `degit https://github.com/froko/vite-ts-lit`
- Create a brand new GIT repo: `git init && git add . && git commit -m "Initial Commit"`

  Please note: Because Husky will be prepared during dependency installation, we will have a Git repo in place beforehand.

- Download dependencies: `npm install`
- Start coding

Husky will automatically format and lint your staged files before you commit your changes.

## Available npm scripts

- `npm start`: Starts vite dev server & serves project at `http://localhost:3000`
- `npm run format`: Formats your files with Prettier
- `npm run build`: Does TypeScript transpilation & bundling of all your assets into the `dist` folder
- `npm run preview`: Serves the built web app at `http://localhost:4173`
