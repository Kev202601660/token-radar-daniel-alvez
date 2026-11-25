# token-radar-daniel-alvez

[![make.fun · token-radar-01](https://make.fun/badge/token-radar-01.svg)](https://make.fun/bounty/token-radar-01)
[![rank](https://make.fun/badge/token-radar-01/Kev202601660/token-radar-daniel-alvez/rank.svg)](https://make.fun/bounty/token-radar-01/leaderboard)
[![reward](https://make.fun/badge/token-radar-01/Kev202601660/token-radar-daniel-alvez/reward.svg)](https://make.fun/bounty/token-radar-01/leaderboard)

A token launch radar: reads the sealed DefiLlama snapshot, ranks pre-token protocols by a sector-comparable implied value, and renders a filterable dashboard with a farm plan per protocol. Built for [make.fun](https://make.fun/bounty/token-radar-01).

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts --input ../token-radar-01-kit/input/snapshot.json
```
