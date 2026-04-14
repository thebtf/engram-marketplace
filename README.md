# engram-marketplace

Claude Code plugin marketplace index for [engram](https://github.com/thebtf/engram).

Plugin files are synced from the main engram repo's
[`plugin/engram/`](https://github.com/thebtf/engram/tree/main/plugin/engram) directory.
This repo exists to keep marketplace installs lightweight (~100 KB vs ~400 MB full repo).

## Install

```
/plugin marketplace add thebtf/engram-marketplace
/plugin install engram
```

Claude Code will prompt for `server_url` and `api_token` on first use,
then automatically download the engram binary for your platform.
