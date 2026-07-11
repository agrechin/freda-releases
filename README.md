# freda — releases

Prebuilt binaries for **freda**, a CLI that archives
[Fireflies.ai](https://fireflies.ai) meeting transcripts as Markdown to local
directories and/or Google Cloud Storage buckets, and can safely prune them
from Fireflies once they are archived.

**📖 Documentation: [agrechin.github.io/freda](https://agrechin.github.io/freda/)**

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

> **Note:** releases are tested only on macOS. The Linux and Windows binaries
> are cross-compiled and published untested — they are expected to work, but
> treat them as best-effort and
> [report anything broken](https://github.com/agrechin/freda-releases/issues).

## License

Binaries are distributed under the [MIT License](LICENSE).
