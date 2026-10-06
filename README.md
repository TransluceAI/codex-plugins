# Codex Plugins

A collection of plugins for Codex.

## Available Plugins

| Plugin | Description |
|--------|-------------|
| [docent](./plugins/docent) | Docent AI analysis tools for Codex |
| [fxtr](./plugins/fxtr) | Skills for writing, running, and viewing fxtr experiments, and for calling models from them with behaviors |

The fxtr plugin includes two skills, each with a copy of the documentation it links from
[docs.transluce.ai](https://docs.transluce.ai):
- **fxtr** - Setting up, writing, running, and viewing fxtr experiments
- **behaviors** - Calling language models from fxtr experiments with the behaviors library

The fxtr plugin is generated from the fxtr repository by `pnpm sync:plugin`; don't edit it by hand.

## Installation

Add this marketplace to Codex:

```shell
codex plugin marketplace add TransluceAI/codex-plugins
```

Then install a plugin:

```shell
codex plugin add docent@transluce-plugins
codex plugin add fxtr@transluce-plugins
```
