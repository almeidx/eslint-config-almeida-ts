# eslint-config-almeida-ts

Strict ESLint config that I use for TypeScript.

## Instalation
```
yarn add eslint eslint-config-almeida-ts -D
```

Or if you're using npm:
```
npm i eslint eslint-config-almeida-ts --save-dev
```

## Configuration
Create a `.eslintrc.json` file on the root directory your project with:
```json
{
  "extends": "almeida-ts",
  "parserOptions": {
    "project": "./path/to/tsconfig.json"
  }
}
```
