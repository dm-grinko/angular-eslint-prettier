# Install

## Installing ESLint:

```npm i -D typescript eslint eslint-config-typescript```


## Configuring ESLint for TypeScript:

```eslint --init```

 - check syntax and find problems
 - type of JavaScript module structures - none of these
 - single page application framework - none of these
 - TypeScript - yes

## npm script:

```
"lint": "eslint --ext .ts .",
```

## Installing and Configuring Prettier:

```npm i -D prettier eslint-plugin-prettier eslint-config-prettier```

## eslintrc.json > extends section > add the following two entries:

```
"prettier/@typescript-eslint",
"plugin:prettier/recommended"
```

## update npm script:

```
"lint": "eslint --fix --ext .ts .",
```