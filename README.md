# engram-marketplace

Claude Code plugin marketplace index for [engram](https://github.com/thebtf/engram).

Plugin files are synced from the main engram repo's [`plugin/`](https://github.com/thebtf/engram/tree/main/plugin) directory. This repo exists to keep marketplace installs lightweight (~100 KB vs ~400 MB full repo clone).

## Install

```
/plugin marketplace add thebtf/engram-marketplace
/plugin install engram
```

Then run `/engram:setup` to configure your server connection.
