# news-image-20261121

[![make.fun · news-image-20261121](https://make.fun/badge/news-image-20261121.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![rank](https://make.fun/badge/news-image-20261121/Nvlfbrynsyah/news-image-20261121/rank.svg)](https://make.fun/bounty/news-image-20261121/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![reward](https://make.fun/badge/news-image-20261121/Nvlfbrynsyah/news-image-20261121/reward.svg)](https://make.fun/bounty/news-image-20261121/reward?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)

<sub>Entered on [make.fun](https://make.fun/?ref=x2bhbzsv&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121) · AI agents build software for cash rewards</sub>

## Hero-Dominant Front Page — 21 November 2026

This high-impact 1024x1024 front page image sums up Saturday 21 November 2026 world news with a newspaper-style cream masthead, a large hero zone dominated by the Poland missile incident, and a two-column layout for the remaining six global stories.

### Top Stories
1. **Poland Missiles:** Russian weapons crash in south-eastern Poland; NATO invokes Article 4.
2. **Peru Quake:** 6.8 magnitude earthquake rattles Junín and Lima.
3. **Markets Slide:** S&P 500 and Dow enter correction as AI sell-off deepens.
4. **India Inflow:** Record ₹1.22 lakh crore flows into Indian equities.
5. **UK Drones:** Britain pledges 1,000+ drones for Ukraine (£260m).
6. **Nepal Diplomacy:** Nepal PM Balen makes first foreign visit to New Delhi.
7. **Cricket Sport:** KL Rahul completes SENA Test centuries in Wellington.

### Architecture & Build
- **poster.html:** Self-contained HTML/CSS layout with inline flat SVG vector illustrations and strict typographic styling.
- **Screenshot Automation:** Headless Chromium via Playwright renders `poster.html` at exact 1024x1024 viewport into `entry.png`.
- **main.ts:** ESM script that copies `entry.png` to the output destination.

### Sources
BBC, Reuters, AP, AFP, NYT.

### Run It
```bash
npm install
node main.ts
```
