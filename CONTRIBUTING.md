# How to contribute

We love pull requests. And following this guidelines will make your pull request easier to merge.

If you want to contribute but don’t know what to do, take a look at these two labels: [help wanted](https://github.com/ninetails/monorepo-releases-poc/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22) and [good first issue](https://github.com/ninetails/monorepo-releases-poc/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22).

## Prerequisites

- If it’s your first pull request, watch [this amazing course](http://makeapullrequest.com/) by [Kent C. Dodds](https://twitter.com/kentcdodds).
- Install [EditorConfig](https://editorconfig.org/) plugin for your code editor to make sure it uses correct settings.
- Fork the repository and clone your fork.

## Installation

### Using npm

```sh
$ npm run reset
$ npm run bootstrap
```

### Using Yarn 1 (Classic)

```sh
$ yarn reset
```

### Using Yarn 2 (Berry)

Just run

```sh
$ yarn
```

#### If you're using Yarn 2 (or Yarn v1.x with PnP)

Execute this to integrate **VSCode** with **TypeScript**:

```sh
$ yarn dlx @yarnpkg/pnpify --sdk vscode
```

## Development workflow

> @todo

## Other npm commands

- **clean** - Remove some generated files related to this project
- **reset** - Run above before installing dependencies (don't work with Yarn 2)

## Other notes

- If you have commit access to repository and want to make big change or not sure about something, make a new branch and open pull request.
- Don’t commit generated files, like minified JavaScript.
- Don’t change version number and changelog.
