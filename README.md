# ALLYK Diagnostics Claude marketplace

This is the public Claude Code marketplace for the [ALLYK Diagnostics](https://github.com/mayayaiinfra/allyk-diagnostics-claude-plugin) plugin.

## Install in Claude Code

```text
/plugin marketplace add mayayaiinfra/allyk-diagnostics-claude-marketplace
/plugin install allyk-diagnostics@allyk-diagnostics
```

Review the marketplace and plugin source before installing. The plugin exposes only the bounded ALLYK Diagnostics MCP operations: preview an assessment, save a review to a selected Roadmap task, and read bounded review history. It does not expose ALLYK conversations, files, credentials, billing, private calculations, internal agents, or arbitrary actions.

The public plugin repository is also suitable for Claude directory review. Directory submission and availability are controlled by Anthropic.

## Repository layout

- `.claude-plugin/marketplace.json` describes the marketplace and points to the public plugin repository.
- `allyk-diagnostics-claude-plugin` contains the versioned plugin package and its MCP configuration.

## License

The marketplace metadata and the referenced plugin are proprietary to MAYAYAI. See the plugin repository's [LICENSE](https://github.com/mayayaiinfra/allyk-diagnostics-claude-plugin/blob/main/LICENSE).
