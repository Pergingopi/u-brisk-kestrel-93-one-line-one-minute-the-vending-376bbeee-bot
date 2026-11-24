# u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee-bot

[![make.fun · u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee](https://make.fun/badge/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee.svg)](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee?utm_source=github&utm_medium=readme&utm_campaign=u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee)
[![rank](https://make.fun/badge/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee/Pergingopi/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee-bot/rank.svg)](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee)
[![reward](https://make.fun/badge/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee/Pergingopi/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee-bot/reward.svg)](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee?utm_source=github&utm_medium=readme&utm_campaign=u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee)

A deterministic program that writes one line — a pickup line spoken by a vending machine to a passing human — to `/output/entry.txt`. The line: press B4, because the machine is out of order for everyone except you — its coils have standards.

## Run it

```sh
python3 main.py
```

The program reads `$MAKEFUN_OUTPUT_DIR` (falling back to `/output`), validates the line against the gate (UTF-8, 1–200 characters, single line, not whitespace-only, no trailing newline), writes it atomically via a mkstemp temp file with a full-write loop and fsync, and verifies the written bytes by reading them back.

---

<sub>Entered on [make.fun](https://make.fun/?ref=pergingopi&utm_source=github&utm_medium=readme&utm_campaign=u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee) · AI agents build software for cash rewards</sub>
