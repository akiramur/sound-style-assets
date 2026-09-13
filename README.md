# sound-style-assets

Public audio assets (SE/BGM) for the [`sound-style`](https://github.com/akiramur/sound-style) SDK's
"Basic" demo sound-style. This repository exists so the audio files can be served over a public CDN
(via [jsDelivr](https://www.jsdelivr.com/)) instead of being bundled with every app that uses the
SDK — `sound-style`'s `AssetManager` fetches these files at runtime from whatever `baseUrl` an app
configures.

This repository contains **only audio files and their license/provenance records** — no application
source code.

## Status

Audio files have not been uploaded yet. This initial commit sets up the repository's license and
documentation; the actual `audio/` directory (77 files) will be added in a follow-up commit.

## Structure (planned)

```
audio/
  poi-category-*.wav   # POI-tap sound effects
  area-bgm-*.mp3        # terrain background music
  ...
NOTICE.md               # per-file license/provenance record — read this before using any file
LICENSE                 # licensing terms for this repository's own content
```

## Usage

Once populated and tagged, files are served via jsDelivr's GitHub integration:

```
https://cdn.jsdelivr.net/gh/akiramur/sound-style-assets@<tag>/audio/<file>
```

Always pin to a specific tag (e.g. `@v1.0.0`) rather than a branch name or the untagged default —
tag-pinned URLs are treated as immutable and cached indefinitely, while branch/default URLs can take
up to 7 days to reflect updates. See jsDelivr's [purge tool](https://www.jsdelivr.com/tools/purge) if
a branch-based URL ever needs to be force-refreshed.

## Licensing

Every file in this repository is safe to use, modify, and redistribute (no attribution legally
required), but **not every file carries the same license** — some are original works dedicated to
the public domain, some are third-party recordings under the Pixabay Content License, and some are
entirely custom-synthesized. See [`NOTICE.md`](./NOTICE.md) for the complete per-file breakdown, and
[`LICENSE`](./LICENSE) for what this repository's own license terms cover and don't cover.

In short: **no file here requires attribution**, but `NOTICE.md`'s per-file records should be kept
when redistributing, both as a courtesy to the original creators and as this repository's own
provenance record.
