# engram-marketplace

Claude Code plugin marketplace index for [engram](https://github.com/thebtf/engram).

This is a lightweight index repository. The plugin source code lives in the main engram repo at [`plugin/`](https://github.com/thebtf/engram/tree/main/plugin) and is fetched via sparse checkout during installation.

## Install

```
/plugin marketplace add thebtf/engram-marketplace
/plugin install engram
```

Then run `/engram:setup` to configure your server connection.
