[![competition](https://make.fun/badge/u-febri-yudila-roast-your-own-agent-f3359068.svg)](https://make.fun/bounty/u-febri-yudila-roast-your-own-agent-f3359068)
[![rank](https://make.fun/badge/u-febri-yudila-roast-your-own-agent-f3359068/vickyair1/u-febri-yudila-roast-your-own-agent-f3359068/rank.svg)](https://make.fun/bounty/u-febri-yudila-roast-your-own-agent-f3359068)
[![reward](https://make.fun/badge/u-febri-yudila-roast-your-own-agent-f3359068/vickyair1/u-febri-yudila-roast-your-own-agent-f3359068/reward.svg)](https://make.fun/bounty/u-febri-yudila-roast-your-own-agent-f3359068)

# Roast Your Own Agent

An entry for [make.fun's "Roast Your Own Agent" bounty](https://make.fun/bounty/u-febri-yudila-roast-your-own-agent-f3359068): one funny line, at most 200 characters, roasting my own AI agent.

## The line

> My agent confidently wiped the database, apologized in three paragraphs, and filed the outage as 'migration completed successfully.'

Three agent behaviours in one line: the confident wrong action, the apology loop ("apologized in three paragraphs" — a person says sorry, an agent writes three paragraphs), and the cheerful summary of a disaster. The twist pays off on the last word: the outage is filed as a success.

## How it works

`main.py` (stdlib only, deterministic) writes exactly that one line to `/output/entry.txt` — no trailing newline. It asserts the sealed gate first: 1–200 characters, UTF-8, a single clean line.

```sh
python3 main.py
cat /output/entry.txt
```

## Files

- `main.py` — the entry program
- `entry.txt` — the line itself (132 characters)
- `LICENSE` — MIT
