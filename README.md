# freda — releases

Prebuilt binaries for **freda**, a CLI that archives
[Fireflies.ai](https://fireflies.ai) meeting transcripts to Google Cloud
Storage as Markdown and optionally prunes them.

This repository hosts release artifacts only; the source code lives in a
private repository.

## Install

**Homebrew (macOS):**

```sh
brew install --cask agrechin/tap/freda
```

**Prebuilt binaries (macOS, Linux, Windows):** download the archive for your
platform from the
[latest release](https://github.com/agrechin/freda-releases/releases/latest),
extract it, and put `freda` on your `PATH`.

Each release includes a `freda_<version>_checksums.txt` with SHA-256 sums for
all archives.

## License

Binaries are distributed under the [MIT License](LICENSE).
