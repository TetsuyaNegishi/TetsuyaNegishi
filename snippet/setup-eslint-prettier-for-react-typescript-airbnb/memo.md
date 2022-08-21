
## install

```
npm install --dev eslint eslint-config-airbnb eslint-config-airbnb-typescript eslint-config-prettier eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-react eslint-plugin-react-hooks eslint-plugin-unused-imports prettier
```

## npm script

```
{
  "scripts": {
    "lint": "eslint './**/*.{js,jsx,ts,tsx}'",
    "lint:fix": "eslint --fix './**/*.{js,jsx,ts,tsx}'",
    "format": "prettier --write './**/*.{js,jsx,cjs,ts,tsx,css,md,json}' --config ./.prettierrc.json"
	}
}
```
