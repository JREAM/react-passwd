# React Password Generator

- [Vite](https://vitejs.dev/)
- [TypeScript](https://www.typescriptlang.org/)

 📖 **[Preview Project](https://jream.github.io/react-passwd/)**

## Installation

I am using [PNPM](https://pnpm.io/). Run the following:

```bash
pnpm i
pnpm start

# For NPM
npm i
npm run start
```

## Deploy to GH-Pages

At the moment I'm using [Vite](https://vitejs.dev/) and a minimal React setup. I modify `vite.config.ts` with the `base` URL set to `./` so that it appears on GH-Pages without a invalid `text/html` MIME type.

These two items in `package.json` are part of the `gh-pages` npm package:

```json
  "predeploy": "pnpm run build",
  "deploy": "gh-pages -d dist",
```

Simply run, `npm run deploy` and it will create a branch and transpile the project.

---

> MIT Open Source
> &copy; 2024 [JREAM](https://jream.com) | Jesse Boyer