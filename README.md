# To Test
Uncomment `pnpm lint-staged` in `.husky/pre-commit`
Make any change in `src/ignore/main.tsx`. This file should be ignored by the config from any formatting. but when staged and trying to commit, it will fail.
