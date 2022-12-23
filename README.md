# React Webpack Typescript Starter

> Minimal starter with hot module replacement (HMR) for rapid development.

- **[React](https://facebook.github.io/react/)** (18.x)
- **[Webpack](https://webpack.js.org/)** (5.x)
- **[Typescript](https://www.typescriptlang.org/)** (4.x)
- **[Hot Module Replacement (HMR)](https://webpack.js.org/concepts/hot-module-replacement/)** + [Fast Refresh](https://github.com/pmmmwh/react-refresh-webpack-plugin)
- Image support ([Image Webpack Loader](https://github.com/tcoopman/image-webpack-loader))
- [SASS](http://sass-lang.com/) support
- Production build script
- Code linting ([ESLint](https://github.com/eslint/eslint)) and formatting ([Prettier](https://github.com/prettier/prettier))
- Test frameworks ([Jest](https://facebook.github.io/jest/) + [React Testing Library](https://testing-library.com/docs/react-testing-library/intro))

## Installation

1. Clone/download repo
2. `yarn install` (or `npm install` for npm)

## Usage

**Development**

`yarn start`

- Build app continuously (HMR enabled)
- App served @ `http://localhost:3000`

**Production**

`yarn start-prod`

- Build app once (HMR disabled) to `/build/`
- App served @ `http://localhost:3000`

---

**All commands**

| Command               | Description                                                                    |
| --------------------- | ------------------------------------------------------------------------------ |
| `yarn run start`      | Build app continuously (HMR enabled) and serve @ `http://localhost:3000`       |
| `yarn run start-prod` | Build app once (HMR disabled) to `/build/` and serve @ `http://localhost:3000` |
| `yarn run build`      | Build app to `/build/`                                                         |
| `yarn run lint`       | Run linter                                                                     |
| `yarn run format`     | Run linter and fix issues                                                      |

**Note**: replace `yarn` with `npm` in `package.json` if you use npm.

## See also

- [Create React App](https://github.com/facebook/create-react-app)
