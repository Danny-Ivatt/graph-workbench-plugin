# Graph analytics workbench: plugin for Claude

This repository is the marketplace for the graph analytics workbench's plugin. It is published automatically; don't edit it here.

The plugin brings:
- the workbench's connector;
- a support checker, which judges facts from the sentences they cite;
- a reviewer, which reads answers as a sceptical outside reader.

It holds no method of its own: each helper reads the workbench's guides, which come through the connector.

To add it in Claude: Customize, then Plugins, then Add, then Add marketplace. Enter this repository, and turn on Sync automatically so updates arrive by themselves.

In Claude Code:

```
/plugin install graph-workbench --marketplace Danny-Ivatt/graph-workbench-plugin
```
