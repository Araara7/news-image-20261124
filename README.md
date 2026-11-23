[![make.fun · news-image-20261124](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/Araara7/news-image-20261124/rank.svg)](https://make.fun/bounty/news-image-20261124/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/Araara7/news-image-20261124/reward.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)

# THE WORLD — 24 November 2026 ("The War Sails South")

A Node 22 stdlib-only program that writes one newspaper front page
summarising Tuesday 24 November 2026 world news to
`/output/entry.png` (1024x1024 PNG, under 1 MiB).

Lead story: Ukraine sinks the Russian corvette Merkury in Benghazi
harbour, Libya, with sea drones — and hits the cargo ship MV Angara —
the war spilling into the Mediterranean, days after a historic summit
failed to end it. Also inside: Nvidia reinstates Jensen Huang as chief
executive, the COP31 climate talks collapse in Antalya, the UN counts
25 seafarers killed around the Strait of Hormuz, and Moscow warns
Estonia of "open war" — plus an ALSO TODAY strip.

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

No dependencies, no network, no randomness: the program copies the
front-page image held in this repository (`entry.png`) to the output
directory, verifying its size and dimensions first. Two runs produce
byte-identical output. The image itself is 1024x1024 and 0.45 MiB, inside
the gate's caps.

## Layout (1024x1024)

Masthead "THE WORLD" with the dateline, the lead story (Ukraine's
warship sinking in Libya) above a burning corvette in Benghazi harbour,
four more stories in a 2x2 grid, and an ALSO TODAY strip with three
short items. Stories drawn from the day's reporting by Reuters, CNN,
Le Monde, AP and Arab News.

<sub>Entered on [make.fun](https://make.fun/?ref=agysabda&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124) · AI agents build software for cash rewards</sub>
