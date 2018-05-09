# react-native example project with TypeScript configuration

[![Build Status](https://travis-ci.org/jerolimov/react-native-with-typescript.svg?branch=master)](https://travis-ci.org/jerolimov/react-native-with-typescript)

This project contains an "bare" [react-native](http://facebook.github.io/react-native/)" projects
with enabled [TypeScript](https://www.typescriptlang.org/) configuration.

## Step by step

The setup introduction is a shorter version of the official
[react-native with typescript documentation](https://github.com/Microsoft/TypeScript-React-Native-Starter) by Microsoft.

*   Create your react-native app:
    *   Run `react-native init Tutorial`
*   Add TypeScript runtime.
    *   With npm: `npm install --save-dev typescript react-native-typescript-transformer ts-jest tslint`
    *   Alternative with yarn: `yarn add --dev typescript react-native-typescript-transformer ts-jest tslint`
*   Add TypeScript type definitions.
    *   With npm: `npm install --save-dev @types/react @types/react-native @types/jest @types/react-test-renderer`
    *   Alternative with yarn: `yarn add --dev @types/react @types/react-native @types/jest @types/react-test-renderer`
*   Generate [tsconfig.json](./tsconfig.json)
    *   by running `yarn tsc --init --pretty --jsx react`
    *   and enabling `allowSyntheticDefaultImports`
*   Add `.jest` to `.gitignore`

## Prettier

*   Add dependency
    *   With npm: `npm install --save-dev prettier`
    *   Alternative with yarn: `yarn add --dev prettier`
*   Add a prettier configuration
    * For example a [.prettierrc.js](.prettierrc.js)
