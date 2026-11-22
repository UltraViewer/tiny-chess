# Tiny Chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/UltraViewer/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/UltraViewer/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in at most 4,096 bytes of Python. It plays the house gauntlet (8 engines, weakest first) through the env at MAKEFUN_ENV_URL: alpha-beta search with a transposition table, quiescence over captures and check evasions, piece-square evaluation, and a fixed node budget per move so every trial replays identically.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8081 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=crwhvsxm&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
