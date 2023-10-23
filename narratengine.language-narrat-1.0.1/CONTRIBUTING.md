# Welcome to Narrat contributing guide.

Thank you for investing your time in contributing to narrat syntax highlighting. Please read our [Code of conduct](CODE_OF_CONDUCT.md) before you start.

This guide contains an overview of how this repo works and how to get started making changes to it.

## Introduction

This repo is a [Visual Studio Code](https://code.visualstudio.com) extension that adds rich support for the [Narrat](https://get-narrat.com) programming language to it.

To know more about how narrat is used, go to [docs.get-narrat.com](https://docs.get-narrat.com/).

## How to contribute

The language uses the standard [TextMate grammar](https://www.apeth.com/nonblog/stories/textmatebundle.html) syntax, as explained in the [VS Code syntax highlighting extensions docs](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide).

We also use yaml files to edit the configuration (as that's easier to write). They get compiled to json with the npm `compile` script.

To edit the syntax highlighting, simply start editing the yaml file in the `syntaxes` folder.

See [The quickstart readme](./vsc-extension-quickstart.md) for more information.

## Opening PRs

Feel free to open a PR for any improvement

## Opening issues

Feel free to open an issue for any problem
