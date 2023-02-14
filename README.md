# eslint-config-react

[![npm version](https://badge.fury.io/js/@calblueprint%2Feslint-config-react.svg)](https://badge.fury.io/js/@calblueprint%2Feslint-config-react)

This package provides a shared ESLint configuration for use on React projects.

## Usage

1. Install this package as a development dependency:

    ```sh
    # with npm
    npm install --save-dev @calblueprint/eslint-config-react

    # with yarn
    yarn add --dev @calblueprint/eslint-config-react
    ```

2. Install peer dependencies:

    ```sh
    # with npm or yarn
    npx install-peerdeps --dev @calblueprint/eslint-config-react
    ```

3. Use the shared ESLint config in your project's `.eslintrc.js`:
   
    ```js
    module.exports = {
      extends: ['@calblueprint/eslint-config-react'],
    };
    ```

4. Test that the config is working by running `npx eslint .` in your project's root directory.