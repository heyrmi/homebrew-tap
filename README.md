# homebrew-tap

Homebrew casks for [heyrmi](https://github.com/heyrmi)'s tools.

```sh
brew install heyrmi/tap/<name>
```

`heyrmi/tap` is Homebrew's shorthand for this repository — there is no need to
`brew tap` it first.

## What is here

| Cask | What it is |
|---|---|
| `testground` | [A deterministic, offline playground of browser-automation challenges](https://github.com/heyrmi/testground) for QA engineers |

## How casks get here

Nothing in this repository is written by hand. Each project's release pipeline
commits its own cask into `Casks/` when it is tagged, so the version here is
whatever that project released last. Editing a cask directly would be undone by
the next release.
