# homebrew-vicine-cli

Homebrew tap for [vicine](https://github.com/spaciousejar/vicine-cli) — search, stream, and download movies, series and anime from the terminal.

## Install

```bash
brew tap spaciousejar/vicine-cli
brew install vicine
```

Then `vicine --help`.

## What is in here

One file: `Formula/vicine.rb`. The formula installs the release tarball from
`spaciousejar/vicine-cli` and declares its dependencies (`fzf`, `jq`, `yt-dlp`,
and the IINA cask on macOS). No vicine source is vendored here.

## License

GPL-3.0-or-later, matching the software this tap installs. See [LICENSE](LICENSE).
