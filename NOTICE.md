# Audio Asset License Notice

This document records the license and provenance of every audio file in this repository's `audio/`
directory (the `sound-style` SDK's "Basic" demo sound-style — 77 files). **No file listed here
requires attribution to use, modify, or redistribute.** See [`LICENSE`](./LICENSE) for how this
repository's own license terms relate to the third-party licenses below.

## Summary by license

| License | File count | Attribution required? |
|---|---|---|
| Custom synthesis (copyright-free / CC0, see below) | 12 | No |
| Pixabay Content License | 59 | No |
| CC0 (Public Domain, OpenGameArt.org) | 5 | No |
| CC0 + custom synthesis (mixed, see `poi-sfx.wav` below) | 1 | No |

## A note on the Pixabay Content License's "Standalone" clause

Pixabay's [Content License](https://pixabay.com/service/license/) permits free commercial and
non-commercial use and modification without attribution, but prohibits distributing Pixabay content
"on a Standalone basis" — defined as content to which "no creative effort has been applied" and
which "remains in substantially the same form as it exists on [Pixabay's] website." Every
Pixabay-sourced file in this repository has been edited (trimmed, faded, gain-adjusted, and/or mixed
with other recordings) before use, and is served here as a specific asset consumed programmatically
by the `sound-style` SDK — not offered as a general-purpose downloadable sound-effect library — so
this restriction does not apply to these files as distributed here.

## Custom-Synthesized Audio (12 files)

Entirely custom-synthesized — not a sample or melody quotation of any real-world recording or
performance. No third-party rights apply; dedicated to the public domain (CC0) by this project.

- `ease-glide.wav`
- `flyto-whoosh.wav`
- `jump-teleport.wav`
- `sky-sfx.wav`
- `gb-country-bgm.wav`
- `jp-country-bgm-forest.wav`
- `jp-country-bgm-urban.wav`
- `jp-country-bgm-urban-night.wav`
- `jp-forest-night-bgm.wav`
- `light-terrain-bgm.wav`
- `poi-category-station.wav` (a synthesized railroad-crossing-alarm-bell-style sound)
- `poi-category-bus-stop.wav` (a synthesized two-tone "next stop" transit bell)

## Pixabay Content License (59 files)

Real recordings sourced from [Pixabay](https://pixabay.com/), each edited (trimmed, faded,
gain-adjusted, and/or mixed with another Pixabay recording) before use. Usable for free, commercially
or non-commercially, with modification permitted and no attribution required, per the
[Pixabay Content License](https://pixabay.com/service/license/).

- `traffic-jam.wav`
- `weather-rain-ambient.wav`
- `weather-storm-ambient.wav`
- `poi-category-airport-sydney.wav`
- `poi-category-alcohol-shop.wav`
- `poi-category-amusement-park.wav`
- `poi-category-aquarium.wav`
- `poi-category-attraction.wav`
- `poi-category-bar.wav`
- `poi-category-basketball.wav`
- `poi-category-beach.wav`
- `poi-category-bicycle.wav`
- `poi-category-bowling.wav`
- `poi-category-car.wav`
- `poi-category-car-repair.wav`
- `poi-category-car-wash.wav`
- `poi-category-casino.wav`
- `poi-category-castle.wav`
- `poi-category-cemetery.wav`
- `poi-category-college-library.wav`
- `poi-category-communications-tower.wav`
- `poi-category-dentist.wav`
- `poi-category-dog-park.wav`
- `poi-category-farm.wav`
- `poi-category-fire-station.wav`
- `poi-category-fuel.wav`
- `poi-category-golf.wav`
- `poi-category-heliport.wav`
- `poi-category-highway.wav`
- `poi-category-horse.wav`
- `poi-category-hot-spring.wav`
- `poi-category-industrial.wav`
- `poi-category-information.wav`
- `poi-category-landmark.wav`
- `poi-category-laundry.wav`
- `poi-category-monument.wav`
- `poi-category-music.wav`
- `poi-category-parking.wav`
- `poi-category-police.wav`
- `poi-category-racetrack.wav`
- `poi-category-religious-buddhist.wav`
- `poi-category-religious-christian.wav`
- `poi-category-religious-jewish.wav`
- `poi-category-religious-muslim.wav`
- `poi-category-religious-shinto.wav`
- `poi-category-restaurant.wav`
- `poi-category-school.wav`
- `poi-category-shop.wav`
- `poi-category-skateboard.wav`
- `poi-category-stadium.wav`
- `poi-category-table-tennis.wav`
- `poi-category-tennis.wav`
- `poi-category-theatre.wav`
- `poi-category-toilet.wav`
- `poi-category-veterinary.wav`
- `poi-category-volleyball.wav`
- `poi-category-waterfall.wav`
- `poi-category-windmill.wav`
- `poi-category-zoo.wav`

## CC0 / Public Domain music tracks (5 files, from OpenGameArt.org)

Terrain/world-view BGM tracks, each an unmodified or lightly gain-adjusted CC0-licensed piece of
music (no derivative-work restriction applies either way).

| File | Track title | Author | Source |
|---|---|---|---|
| `area-bgm-urban.mp3` | Town Theme RPG | cynicmusic | https://opengameart.org/content/town-theme-rpg |
| `area-bgm-sea.mp3` | Feel Good Island Loop | AntumDeluge (based on Brandon Morris) | https://opengameart.org/content/feel-good-island-loop |
| `area-bgm-desert.mp3` | Desert Loop | iamoneabe | https://opengameart.org/content/desert-loop |
| `area-bgm-forest.mp3` | Peaceful Forest | samza | https://opengameart.org/content/peaceful-forest |
| `world-view-bgm.mp3` | Space Music: Out There | yd | https://opengameart.org/content/space-music-out-there |

## `poi-sfx.wav` (mixed CC0 + custom synthesis)

Two clips (`select`/`deselect`), each a CC0 source sample from Kenney's
[Interface Sounds](https://kenney.nl/assets/interface-sounds) pack (obtained via the
[GitHub mirror](https://github.com/Calinou/kenney-interface-sounds)) with a custom-synthesized decay
tail added.

| Segment | Source file | Author | License |
|---|---|---|---|
| select | confirmation_002.wav + custom-synthesized decay tail | Kenney (kenney.nl) | CC0 (+ custom-synthesized portion is copyright-free) |
| deselect | close_002.wav + custom-synthesized decay tail | Kenney (kenney.nl) | CC0 (+ custom-synthesized portion is copyright-free) |

Kenney's license carries no attribution requirement, but welcomes optional credit (a mention of
kenney.nl).

---

Please keep this NOTICE file when redistributing any of these audio files.
