# sound-style-assets

Public audio assets (SE/BGM) for the [`sound-style`](https://github.com/akiramur/sound-style) SDK's
demo sound-styles — **Basic** and **Halloween**. This repository exists so the audio files can be
served over a public CDN (via [jsDelivr](https://www.jsdelivr.com/)) instead of being bundled with
every app that uses the SDK — `sound-style`'s `AssetManager` fetches these files at runtime from
whatever `baseUrl` an app configures.

This repository contains **only audio files and their license/provenance records** — no application
source code.

## Structure

```
audio-basic/
  poi-category-*.wav   # POI-tap sound effects
  area-bgm-*.mp3        # terrain background music
  ...
audio-halloween/
  <category>.mp3        # POI-tap sound effects
  halloween-ambient-*.mp3  # terrain background music
  ...
NOTICE.md               # per-file license/provenance record — read this before using any file
LICENSE                 # licensing terms for this repository's own content
```

## Usage

Files are served via jsDelivr's GitHub integration:

```
https://cdn.jsdelivr.net/gh/akiramur/sound-style-assets@<tag>/audio-basic/<file>
https://cdn.jsdelivr.net/gh/akiramur/sound-style-assets@<tag>/audio-halloween/<file>
```

Always pin to a specific tag (e.g. `@v1.1.0`) rather than a branch name or the untagged default —
tag-pinned URLs are treated as immutable and cached indefinitely, while branch/default URLs can take
up to 7 days to reflect updates. See jsDelivr's [purge tool](https://www.jsdelivr.com/tools/purge) if
a branch-based URL ever needs to be force-refreshed.

`v1.0.0` predates the `audio-basic/`/`audio-halloween/` split (Basic Style's files lived at
`audio/<file>` under that tag) — existing consumers pinned to `v1.0.0` are unaffected, since tags are
immutable; only new consumers need the new paths.

## Licensing

Every file in this repository is safe to use, modify, and redistribute (no attribution legally
required), but **not every file carries the same license** — some are original works dedicated to
the public domain, some are third-party recordings under the Pixabay Content License, and some are
entirely custom-synthesized. See [`NOTICE.md`](./NOTICE.md) for the complete per-file breakdown, and
[`LICENSE`](./LICENSE) for what this repository's own license terms cover and don't cover.

In short: **no file here requires attribution**, but `NOTICE.md`'s per-file records should be kept
when redistributing, both as a courtesy to the original creators and as this repository's own
provenance record.
