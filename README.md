
# This application is build whit typeScript and React/Vite inside a tailwind project

Some background information why this project and what i have lurn from it:

just to make sure that i understand good the basics of typescript and tailwind.
in this training project i have lurn some new features whit typscript and some new imports from framer motions that i have to try out more in new projects.
ilove to play a round whit vite and its easy to set up for some show case projecten.

# Tools
npm i framer-motion react-anchor-link-smooth-scroll@1.0.12 @heroicons/react
npm i -D @types/react-anchor-link-smooth-scroll@1.0.2 @types/node
React: https://reactjs.org/
Typescript: https://www.typescriptlang.org/
Typescript Types vs Interfaces: https://tinyurl.com/typescripttypesvs...
Vite: https://tailwindcss.com/docs/guides/vite
Google Fonts: https://fonts.google.com/
Tailwind: https://tailwindcss.com/
Prettier Tailwind Css Plugin: https://github.com/tailwindlabs/prett...
Prettier Tailwind Css Sorting: https://tailwindcss.com/blog/automati...
Hero Icons: https://heroicons.com/
Framer Motion: https://www.framer.com/docs/introduct...
Form Submit: https://formsubmit.co/
React Anchor Link smooth Scroll: https://github.com/mauricevancooten/r...
Cloudflare Pages: https://pages.cloudflare.com/

# npm istall
npm i framer-motion react-anchor-link-smooth-scroll@1.0.12 @heroicons/react
npm i -D @types/react-anchor-link-smooth-scroll@1.0.2 @types/node

# configuration options

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
   parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
   },
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
