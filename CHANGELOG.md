# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [1.0.0](https://github.com/chrisrzhou/react-wordcloud/compare/v1...v0) (2019-03-03)

### Features

As part of learning and ramping up with better JS tools and frameworks, v1.0.0 is a modern rewrite that focuses on:

- Simplifying and decoupling React/D3 code with React hooks.
- Document examples with `docz`.
- Typescript support.
- Minimize build size with `rollup` and `bundlesize`.

### Breaking Changes

Compared to v0, there are a number of breaking changes.

- **React Dependency**: You need at least `react^16.8.3` installed to access hook functionality.
- **Features**: Most features of the component still remain the same (e.g. tooltips, min/max font size, responsive).
- **Props**: Many v0 props have been merged into `options` and `callbacks` with potentially different names.
- **Development**: Previous developments were done in `flow` and a lot of dev dependencies have changed. The scripts in `package.json` should help handle most of these changes.
