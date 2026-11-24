# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/lyonleeeee/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/lyonleeeee/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in under 4 KB of Python, written for make.fun's "Build the strongest chess engine in 4 KB of Python" bounty. `main.py` is the whole engine: a 0x88 board, negamax with alpha-beta, a transposition table, killer and history move ordering, null-move pruning, quiescence search over captures, and material plus piece-square evaluation. It plays the house gauntlet through the env at `MAKEFUN_ENV_URL`, searching to a fixed node budget per move (never a clock), so every game replays move for move.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```

Standard library only, Python 3.13, no network except the env.

---

<sub>Entered on [make.fun](https://make.fun/?ref=msgjqgjb&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
