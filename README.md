# @baltpeter/eslint-config

> The ESLint configs I use for my projects.

This package contains the ESLint configs I use for my projects. You probably don't want to use this unless you're working on a project with me.

TODO: ESLint's new [flat config system](https://eslint.org/blog/2022/08/new-config-system-part-1/) will eliminate the need for manually installing the peer dependencies in consuming projects. Switch to that once it works with the CLI.

## Usage

This package provides different configs for different use cases.

## General

Install this config and its peer dependencies:

```sh
yarn add --dev @baltpeter/eslint-config eslint @typescript-eslint/eslint-plugin eslint-plugin-eslint-comments eslint-plugin-import typescript
```

Then, add the following to your `.eslintrc`:

```json
{
    "root": true,
    "extends": ["@baltpeter/eslint-config"]
}
```

## Preact

Install this config and its peer dependencies:

```sh
yarn add --dev @baltpeter/eslint-config eslint @typescript-eslint/eslint-plugin eslint-plugin-eslint-comments eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-react eslint-plugin-react-hooks typescript
```

Then, add the following to your `.eslintrc`:

```json
{
    "root": true,
    "extends": ["@baltpeter/eslint-config/preact"]
}
```
