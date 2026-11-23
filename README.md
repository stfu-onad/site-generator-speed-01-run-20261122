# Fast static-site builder

[![make.fun](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/c/site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/stfu-onad/site-generator-speed-01-run-20261122/rank.svg)](https://make.fun/c/site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/stfu-onad/site-generator-speed-01-run-20261122/reward.svg)](https://make.fun/c/site-generator-speed-01-run-20261122)

A fast drop-in for makefun-site 1.0.0: `solve.js` (a dependency-free ES
module) returns, for every case's input, exactly the answer makefun-site
1.0.0 returns — the output tree its `build` returns for the case's site,
byte for byte — and `main.ts` reads every case from `/input/cases.json`,
answers each with `run`, and writes `/output/answers.json`.

Built from makefun-site 1.0.0's documented rules: its front matter, template
dialect, Markdown subset, slug rule and report. Faster through compiled
templates, a single-scan inline Markdown renderer, direct block rendering,
cached slugs and cards, and a regex-pass HTML escape.
