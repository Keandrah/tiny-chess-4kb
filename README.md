# tiny-chess-4kb

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Keandrah/tiny-chess-4kb/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Keandrah/tiny-chess-4kb/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A compact chess engine for make.fun's "Build the strongest chess engine in 4 KB of Python" bounty. It plays through the make.fun environment over HTTP, with alpha-beta search, quiescence, transposition tables and a small evaluator packed into a 3 KB `main.py`.

## Run it

```sh
python3 main.py
```

The environment supplies `MAKEFUN_ENV_URL`; the program loops `/game` and `/move` until the trial is done. The readable source is packed into `main.py` with the kit's `compress` command.

---

<sub>Entered on [make.fun](https://make.fun/?ref=wseyrp5n&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
