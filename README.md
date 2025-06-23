# TypeScript Vanilla Library Template

Template for creating a library using TypeScript with a fully customized environment.

## Features

* ✨ Fully customized [eslint](https://eslint.org/) configuration inspired by the configs by [unjs](https://github.com/unjs/eslint-config), [Antfu](https://github.com/antfu/eslint-config) and [sxzz](https://github.com/sxzz/eslint-config)
* 🧪 Write tests quickly and conveniently with [vitest](https://vitest.dev/)
* 🤝 Supports [conventional commits](https://www.conventionalcommits.org/) with [gitmoji](https://gitmoji.dev)
* 💅 Generate beautiful changelogs with [changelogen](https://github.com/unjs/changelogen)
* ♾️ GitHub CI for your build
* 📢 Issue templates
* 📝 Pull request template
* 🤖 Ready configuration for [renovatebot](https://github.com/apps/renovate) with [renovate-config](https://github.com/hywax/renovate-config)
* ⚒️ Bundle library code using [tsdown](https://tsdown.dev), a modern bundler written on top of [Rolldown](https://rolldown.rs)
* 🚀 Library releases with just one command

## Get started

### GitHub Template

This is a template repo. Click the green [Use this template](https://github.com/bjf5201/typescript-lib/generate) button to get started.

### Git Clone

```shell
git clone https://github.com/bjf5201/typescript-lib.git
cd typescript-lib
pnpm install
```

## Usage

The template contains the following scripts:

* `dev` - Start the development server
* `build` - Build for production
* `release` - Generate changelog and npm publish
* `lint` - Checks for both linting errors and formatting errors
* `typecheck` - Ensure types compile and export correctly
* `test` - Run all tests
* `test:watch` - Run all tests with watch mode
* `prepare` - Script for setting up husky hooks

## License

This template was created under the [MIT License](LICENSE).
