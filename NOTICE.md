# Audio Asset License Notice

This document records the license and provenance of every audio file in this repository. It covers
two independent sound-styles for the `sound-style` SDK: **Basic** (`audio-basic/`, 77 files — this
section) and **Halloween** (`audio-halloween/`, 50 files — its own section further down, which
includes a caveat on 29 of them). **No file listed here requires attribution to use, modify, or
redistribute.** See [`LICENSE`](./LICENSE) for how this repository's own license terms relate to the
third-party licenses below.

## Basic Style — Summary by license

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

## Halloween Style — audio-halloween/ (50 files)

All 50 files are Pixabay downloads, re-encoded to mp3 (44.1kHz stereo, 128kbps) with an edit applied
to every one — trimmed to length with a fade-out, and loudness-normalized (two-pass `loudnorm`) to a
consistent reference level (~-19.5 LUFS for SFX, ~-17.5 LUFS for BGM). Same Pixabay Content License
reasoning as above (every file edited, none served as a general-purpose downloadable library) — no
attribution legally required, credited below anyway where known.

### Confirmed origin (21 files)

| File | Pixabay source |
|---|---|
| `fitness-centre.mp3` | alesiadavina — "Creepy Halloween Horror Voice Run" (vol. 006, #165226) |
| `lodging.mp3` | alesiadavina — "Halloween Horror Voice Hello" (vol. 006, #165220) |
| `casino.mp3` | alesiadavina — "Scary Female Halloween Horror Laughter" (vol. 006, #165223) |
| `bowling-alley.mp3` | charlie_raven — "Halloween Impact 02" (#93804) |
| `baseball.mp3` | charlie_raven — "Halloween Impact 03" (#93806) |
| `basketball.mp3` | charlie_raven — "Halloween Impact 05" (#93808) |
| `library.mp3` | dragon-studio — "Creepy Ghost Whisper" (#410564) |
| `viewpoint.mp3` | dragon-studio — "Creepy Wind" (#410541) |
| `school.mp3` | dragon-studio — "Halloween Ghost Whisper" (#410557) |
| `museum.mp3` | dragon-studio — "Halloween Scary Sound" (#410561) |
| `harbor.mp3` | dragon-studio — "Halloween Wind" (#410540) |
| `fire-station.mp3` | dragon-studio — "Scary Sound" (#410559) |
| `castle.mp3` | dragon-studio — "Spooky Halloween Intro" (#410549) |
| `prison.mp3` | dragon-studio — "Spooky Scary Sound" (#410563) |
| `pharmacy.mp3` | freesound_community — "Witch" (#103635) |
| `toilet.mp3` | fronbondi_skegs — "SFX Halloween Horror Surprise Sound Effect" (#247545) |
| `church-bells.mp3` | idoberg — "Cinematic Halloween Bells Loop" (#421592) |
| `watermill.mp3` | idoberg — "Creepy Halloween Bells Loop" (#408748) |
| `halloween-ambient-sea.mp3` | freesound_community — "Scary Night" (#28893) |
| `halloween-ambient-desert.mp3` | diff_style — "Halloween Moods 6" (#420183) |
| `halloween-ambient-forest.mp3` | audiocoffee — "Halloween Impact" (#167297) |

### Unconfirmed origin (29 files) — provenance gap, published anyway by owner's decision

`alcohol-shop.mp3`, `aquarium.mp3`, `bar.mp3`, `bicycle.mp3`, `car-repair.mp3`, `car-wash.mp3`,
`car.mp3`, `cemetery.mp3`, `crying-woman.mp3`, `dog-park.mp3`, `farm.mp3`, `fuel.mp3`,
`woman-scream.mp3`, `ghost-girl.mp3`, `halloween-ambient-alt.mp3`, `halloween-ambient-night.mp3`,
`haunted-mansion.mp3`, `highway.mp3`, `horse-riding.mp3`, `industry.mp3`, `laundry.mp3`,
`parking.mp3`, `racetrack-horse.mp3`, `restaurant.mp3`, `shop.mp3`, `traffic-sfx.mp3`,
`veterinary.mp3`, `witch-shop.mp3`, `zoo.mp3` predate any provenance record — no original Pixabay
filenames, artist credits, or license text were kept alongside them, and none could be recovered
from git history or a matching raw-download pool. Their encoder fingerprint matches the confirmed
files above, consistent with (but not proof of) the same Pixabay-download-then-edit origin. These
29 files were published here at the repository owner's explicit request, accepting this as an
inferred-not-confirmed provenance gap rather than holding them back; their original Pixabay source
pages should still be re-identified and recorded here when possible. (`woman-scream.mp3`, renamed
from `fuel-boost.mp3` once its content was confirmed, is a +5dB volume-boosted copy of `fuel.mp3`
made in-house, sharing the same origin/license status.)

---

Please keep this NOTICE file when redistributing any of these audio files.
