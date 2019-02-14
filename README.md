# eslint-config-building-app

This package includes the shareable ESLint configuration used by 7r building team.

First, install this package, ESLint and the necessary plugins.

```sh
npm install --save-dev @7r/eslint-config-7r-building babel-eslint@9.x  eslint@5.x  eslint-config-prettier@3.x eslint-plugin-import@2.x eslint-plugin-jsx-a11y@6.x eslint-plugin-prettier@3.x eslint-plugin-react@7.x prettier@1.x
```

Then create a file named `.eslintrc.json` with following contents in the root folder of your project:

```json
{
  "extends": "@7r/eslint-config-7r-building"
}
```

**NB:** if you're using [the extension ESLint for VS Code](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint),
you may want to call that file `.eslintrc` instead, since the extension doesn't seem to find the file otherwise.

That's it! You can override the settings from `eslint-config-7r-building` by editing the `.eslintrc.json` file. Learn more about [configuring ESLint](http://eslint.org/docs/user-guide/configuring) on the ESLint website.
