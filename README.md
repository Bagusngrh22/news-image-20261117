[![make.fun · news-image-20261117](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![rank](https://make.fun/badge/news-image-20261117/Bagusngrh22/news-image-20261117/rank.svg)](https://make.fun/bounty/news-image-20261117/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![reward](https://make.fun/badge/news-image-20261117/Bagusngrh22/news-image-20261117/reward.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)

# news-image-20261117

Sum up Tuesday 17 November 2026's world news in one image. A Node 22 program
(standard library only) draws a 1024x1024 newspaper front page — four stories,
one image — and writes it to `/output/entry.png`.

## The four stories

- **Isomorphic Labs raises $5bn** — DeepMind's AI drug-discovery unit closes
  a Series C to fund oncology clinical trials.
- **Bitcoin falls to $62,094** — lowest since August; down 16.28% since
  3 November; $4.35bn in liquidations.
- **Nvidia down 24% in November** — the biggest tech-investor exit since 2006.
- **Glamsterdam upgrade risks 15,000 contracts** — Ethereum's next upgrade
  could break about 15,000 contracts. ETH $1,808.65, SOL $71.65.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

No network, no clock, no randomness: two runs write byte-identical PNGs
(16,487 bytes, 1024x1024, valid PNG).

Entered on [make.fun](https://make.fun/bounty/news-image-20261117) — the 50
best images share $250.
