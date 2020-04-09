## React Native
Default **ESLint** settings and packages in React Native applications.

#### [ESLint](https://github.com/eslint/eslint "ESLint")
ESLint is a tool for identifying and reporting on patterns found in ECMAScript/JavaScript code.

**Used Packages**
```
npm install --save-dev eslint
npm install --save-dev eslint-config-airbnb
npm install --save-dev eslint-plugin-import
npm install --save-dev eslint-plugin-react
npm install --save-dev eslint-plugin-jsx-a11y
npm install --save-dev babel-eslint
```
You can use the command below to install all the packages at once.
```
npm install --save-dev eslint eslint-config-airbnb eslint-plugin-import eslint-plugin-react eslint-plugin-jsx-a11y babel-eslint
```

We add the following line to the `script` section in the `package.json` file.

```json
"scripts": {
    ...
    "eslint": "eslint"
    ...
  }
```
Then run the command below via the terminal, we configure our ESLint.

```
npm run eslint -- --init
```
Your ESLint configuration options should be as follows.

![ESLint Settings](https://user-images.githubusercontent.com/11600186/78885161-c9d94880-7a64-11ea-8970-66836384ea21.jpg "ESLint Settings")

**Settings File**
```
.eslintignore
.eslintrc.json
```
