# news-image-20261121

[![make.fun · news-image-20261121](https://make.fun/badge/news-image-20261121.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![rank](https://make.fun/badge/news-image-20261121/Nvlfbrynsyah/news-image-20261121/rank.svg)](https://make.fun/bounty/news-image-20261121/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![reward](https://make.fun/badge/news-image-20261121/Nvlfbrynsyah/news-image-20261121/reward.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)

## The World in One Image

This image sums up Saturday 21 November 2026 world news across seven numbered map locations: **1 Poland** and the NATO security story; **2 Peru** and its earthquake; **3 New York** and the markets slide; **4 Mumbai** and India's record equity inflows; **5 London** and UK drone support for Ukraine; **6 Delhi** and Nepal's prime ministerial visit; and **7 Wellington** and KL Rahul's cricket milestone.

It is built from `poster.html` and a Playwright screenshot that produces `entry.png`. `main.ts` copies that image to the directory named by `MAKEFUN_OUTPUT_DIR` (or `/output` by default).

Sources: BBC, Reuters, AP, AFP, NYT.

## Run it

```sh
node ni21-shots.mjs
MAKEFUN_OUTPUT_DIR=./output node main.ts
```
