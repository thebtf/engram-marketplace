# engram-marketplace

Claude Code plugin marketplace index for [engram](https://github.com/thebtf/engram).

This repo is a lightweight index (~1 KB). Plugin files are fetched directly from the
main engram repo via `git-subdir` source — no manual sync needed.

## Install

```
/plugin marketplace add thebtf/engram-marketplace
/plugin install engram
```

Claude Code will prompt for `server_url` and `api_token` on first use,
then automatically download the engram binary for your platform.

## How it works

`marketplace.json` points to `plugin/engram/` in the
[thebtf/engram](https://github.com/thebtf/engram) repository.
Claude Code performs a sparse checkout of just that subdirectory (~100 KB)
instead of cloning the full repo.

To update the plugin version available to users, bump `version` in
`.claude-plugin/marketplace.json` and push.
