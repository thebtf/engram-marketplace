# engram-marketplace

Plugin marketplace index for [engram](https://github.com/thebtf/engram).

Plugin files are synced from the main engram repo's
[`plugin/engram/`](https://github.com/thebtf/engram/tree/main/plugin/engram) directory.
This repo exists to keep marketplace installs lightweight (~100 KB vs ~400 MB full repo).

## Codex Install

```
codex plugin marketplace add thebtf/engram-marketplace
codex plugin add engram@engram-marketplace
```

Configure `ENGRAM_URL` and `ENGRAM_TOKEN` in Codex shell environment policy before
starting a new Codex session.

## Claude Code Install

```
/plugin marketplace add thebtf/engram-marketplace
/plugin install engram
```

Claude Code will prompt for `server_url` and `api_token` on first use,
then automatically download the engram binary for your platform.
