# Static-site generator performance trial

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/nerv00kaworu/makefun-site-speed/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/nerv00kaworu/makefun-site-speed/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

Dependency-free Node.js 22 entry for `site-generator-speed-01-run-20261122`. Run `node main.ts` with input `/input/cases.json` and output `/output/answers.json`; for local use set `MAKEFUN_INPUT_DIR` and `MAKEFUN_OUTPUT_DIR`.

Based on the official MIT-licensed makefun-site 1.0.0 reference. The vendor LICENSE, NOTICE and original provenance are retained. Changes: copy ordinary Markdown text in spans, skip Unicode normalization for ASCII slugs, and memoize short escaped template strings within a single site. No state or lookup tables are carried between cases.

Prepared for [make.fun](https://make.fun/).
