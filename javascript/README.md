# Javascript Project Guideline(s)

It is recommended to use LTS or latest versions of [Node.js](https://nodejs.dev/)

## Code Style

Use [Airbnb's Javascript Style Guide](https://github.com/airbnb/javascript)

## Package Manager

Use [npm](https://www.npmjs.com/). It comes bundled with [Node.js](https://nodejs.dev/)

## Configurations

Some configuration rules might not suit to some projects, so it is recommended to convert those rules to warning setting or use the inline disable syntax, wherever applicable.

The rule can also be disabled if it is being inline-disabled in many files.

It is recommended to create a dedicated config file and include the config in the file.

### [ESLint](https://eslint.org/)

Use [Airbnb's ESlint config](https://www.npmjs.com/package/eslint-config-airbnb-base) -

```sh
npm i eslint-config-airbnb-base
```

### [Prettier](https://prettier.io/)

Use My [Prettier config](https://www.npmjs.com/package/prettier-config-mrdgh2821) -

```sh
npm i prettier-config-mrdgh2821
```
