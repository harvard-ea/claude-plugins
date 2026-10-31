# harvard-ea Claude Code plugins

Plugins for the HUIT Spark Innovation Platform (`inno-platform.spark.huit.harvard.edu`).

```
/plugin marketplace add harvard-ea/claude-plugins
/plugin install innovation-platform@harvard-ea
```

Or from a terminal, with the platform address set:

```
claude plugin marketplace add harvard-ea/claude-plugins
claude plugin install innovation-platform@harvard-ea --config platform_url=https://inno-platform.spark.huit.harvard.edu/mcp
```

| Plugin | Purpose |
| --- | --- |
| [`innovation-platform`](plugins/innovation-platform) | Build and ship apps on the HUIT Spark Innovation Platform. |

The plugin's MCP server is named `inno-platform-spark`, so it can be installed alongside the `davidlaporte` marketplace's `innovation-platform` plugin without a tool-name collision.
