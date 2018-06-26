# init-eslint-react

Initialize an eslint configuration for React &amp; React Native apps.

## Usage

Run the following command in the root folder of your React or React Native project:

```
npx init-eslint-react
```

This will install [`eslint-config-react-app`](https://github.com/facebook/create-react-app/tree/next/packages/eslint-config-react-app#usage-outside-of-create-react-app) and its dependencies, and create a `.eslintrc` file with the following contents:

```
{
  "extends": "react-app"
}
```

With this, your editor should be able to show ESLint warnings if you have the appropriate extension installed. For instance, if you're using VS Code, you should install this extension: https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint .

**NOTE**: This is really just a bash script under the hood, and it hasn't been tested on Windows. Contributions welcome!
