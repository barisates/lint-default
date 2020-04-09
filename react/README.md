## React
Default **ESLint**, **Stylelint** settings and packages in React applications.

#### [ESLint](https://github.com/eslint/eslint "ESLint")
ESLint is a tool for identifying and reporting on patterns found in ECMAScript/JavaScript code.

**Used Packages**
```
npm install --save-dev eslint
npm install --save-dev eslint-config-airbnb
npm install --save-dev eslint-config-react-app
npm install --save-dev eslint-plugin-flowtype
npm install --save-dev eslint-plugin-import
npm install --save-dev eslint-plugin-jest
npm install --save-dev eslint-plugin-jsx-a11y
npm install --save-dev eslint-plugin-react
```

You can use the command below to install all the packages at once.

```
npm install --save-dev eslint eslint-config-airbnb eslint-config-react-app eslint-plugin-flowtype eslint-plugin-import eslint-plugin-jest eslint-plugin-jsx-a11y eslint-plugin-react
```
**Settings File**
```
.eslintignore
.eslintrc.json
```

#### [Stylelint](https://github.com/stylelint/stylelint "Stylelint")

A mighty, modern linter that helps you avoid errors and enforce conventions in your styles.

**Used Packages**
```
npm install stylelint
npm install stylelint-config-standard
```

**Settings File**
```
.stylelintignore
.stylelintrc.json
```

#### Scripts
```json
"scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "test": "set CI=true&&react-scripts test --coverage",
    "eject": "react-scripts eject",
    "lint:css": "stylelint ./src/**/*.css",
    "lint:js": "eslint ./src/**/*.js"
  }
```