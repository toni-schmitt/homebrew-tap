# homebrew-tap

Homebrew formulae for [@toni-schmitt](https://github.com/toni-schmitt)'s tools.

## Install

```sh
brew install toni-schmitt/tap/ember
```

Homebrew expands `toni-schmitt/tap` to this repository, so there is no need to
`brew tap` first.

## Formulae

| Formula | Description |
|---|---|
| [`ember`](Formula/ember.rb) | A two-line status line for [Claude Code](https://code.claude.com), plus a companion subagent row renderer. Source: [toni-schmitt/claude-code-statusline](https://github.com/toni-schmitt/claude-code-statusline) |

## A note on updates

`Formula/ember.rb` is **generated**, not hand-written. The release workflow in
[claude-code-statusline](https://github.com/toni-schmitt/claude-code-statusline)
renders it from `packaging/ember.rb.tmpl` on every non-prerelease tag, filling
in the version and the checksum of each published tarball, then pushes it here.

Send fixes to the template in that repository — edits made directly to the
formula here are overwritten by the next release.
