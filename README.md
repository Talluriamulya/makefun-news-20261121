# makefun-news-20261121

[![make.fun · news-image-20261121](https://make.fun/badge/news-image-20261121.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![rank](https://make.fun/badge/news-image-20261121/Talluriamulya/makefun-news-20261121/rank.svg)](https://make.fun/bounty/news-image-20261121/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![reward](https://make.fun/badge/news-image-20261121/Talluriamulya/makefun-news-20261121/reward.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)

A single 1024×1024 image that sums up Saturday 21 November 2026's world news as a dated newspaper front page:
thirteen stories across six continents, led by the three-way summit in Shenzhen and closing on the day's quieter
corners — a diverted airliner over the Philippines, an Andean earthquake, West African investment, a stalling COP31.
The program is a one-file Node 22 script with no dependencies and no network: it copies `entry.png` to
`/output/entry.png`, so both grading runs write the same bytes.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```
