# eslint-config-building-app

This package includes the shareable ESLint configuration used by 7r building team.

First, install this package.

```sh
npm install --save-dev @7r/eslint-config-7r-building
```

Then create a file named `.eslintrc.json` with following contents in the root folder of your project:

```json
{
  "extends": "@7r/eslint-config-7r-building"
}
```

That's it! You can override the settings from `eslint-config-7r-building` by editing the `.eslintrc.json` file. Learn more about [configuring ESLint](http://eslint.org/docs/user-guide/configuring) on the ESLint website.
