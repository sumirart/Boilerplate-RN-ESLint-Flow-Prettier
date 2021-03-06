# Boilerplate React Native with ESLint, FLow and Prettier

My standard react native app with pre-configured ESLint, Flow, Prettier, Babel.

Tutorial from: https://medium.com/@sgroff04/configure-eslint-prettier-and-flow-in-vs-code-for-react-development-c9d95db07213

## Required Extensions (Using VS Code)

- [ESLint](https://marketplace.visualstudio.com/items?itemname=dbaeumer.vscode-eslint)
- [Prettier - Code Formatter](https://marketplace.visualstudio.com/items?itemname=esbenp.prettier-vscode)
- [Flow Language Support](https://marketplace.visualstudio.com/items?itemname=flowtype.flow-for-vscode)
- [Babel ES6/ES7](https://marketplace.visualstudio.com/items?itemname=dzannotti.vscode-babel-coloring)

## VS Code Settings

Press Ctrl + , (or Cmd + , for Mac), click bracket icon in top right { } and add these code:

```json
"editor.formatOnSave": true,
"eslint.autoFixOnSave": true,
"eslint.alwaysShowStatus": true,
"flow.useNPMPackagedFlow": true,
"javascript.validate.enable": false,
"javascript.format.enable": false,
"prettier.eslintIntegration": true,
```

## Installation

1. Clone project and change folder name

```
git clone https://github.com/sumirart/Boilerplate-RN-ESLint-Flow-Prettier.git change-folder-name
```

2. cd into folder

```
cd change-folder-name
```

3. Download dependencies

```
npm install
```

## Some notes

1. Start flow before doing some code (if it doesn't start already)

```
npm run flow start
```

2. Configure '.eslintrc' if you would like to

3. Add comment '@flow' in top line in every file if you want to use flow

```javascript
//@flow
```

3. Restart VS Code if doens't work

4. Googling if still doesn't work :P
