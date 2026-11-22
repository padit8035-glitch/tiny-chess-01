# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/padit8035-glitch/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/padit8035-glitch/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A tiny Python chess engine (4,061 bytes) for make.fun's `tiny-chess-01` bounty. 0x88 board, alpha-beta search with quiescence and a transposition table, a fixed 125,000-node budget per move. In local trials it scored Elo 1,422 against the sunfish baseline of 1,365.

## Run it

```sh
python3 main.py
```

Python 3.13, standard library only. The grader drives the engine through the competition harness.

---

<sub>Entered on [make.fun](https://make.fun/?ref=tvfbjxfd&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
