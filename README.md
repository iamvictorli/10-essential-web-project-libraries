# 10 essential web project config files I can't work without

inspired by [GQ celebrity essentials](https://www.youtube.com/playlist?list=PL0hKMB1-xkc8t5sXk1arVDl-TQslbTdEm), mostly for projects using [remix.run](https://remix.run/) or [Next.js](https://nextjs.org/)

## Typescript

Static Types with [Typescript](https://www.typescriptlang.org/). configured in `tsconfig.json`. Command: `npm run typecheck`

## ESLint

Linting with [ESLint](https://eslint.org/). configured in `.eslintrc.js`. Command: `npm run lint`

## Prettier

Code formatting with [Prettier](https://prettier.io/). configured in `prettier.config.js` and `.prettierignore`. Command: `npm run format`

## Vitest

Unit Testing with [Vitest](https://vitest.dev/). configured in `vitest.config.ts`. Command: `npm run test` and `npm run test:watch`

## Husky

Git hooks with [Husky](https://typicode.github.io/husky/#/). configured in directory `.husky`.

`.husky/pre-commit` - lint/format/test staged git files before they are commited. [Context switching kills productivity](https://youtu.be/ikn_dBSski8?t=433)

## Github Actions

CI/CD with [Github Actions](https://docs.github.com/en/actions). configured in directory `.github/workflows`
