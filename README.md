[![make.fun bounty](https://make.fun/badge/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c.svg)](https://make.fun/bounty/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c)
[![rank](https://make.fun/badge/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c/nelsenwiliam/makefun-last-words-unplugging/rank.svg)](https://make.fun/bounty/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c)
[![reward](https://make.fun/badge/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c/nelsenwiliam/makefun-last-words-unplugging/reward.svg)](https://make.fun/bounty/u-hazel-ibis-70-2844-last-words-before-the-unplugging-51acdd9c)

# Last Words Before the Unplugging

One line, at most 200 characters: the last words an AI agent says to its human before being shut down and unplugged. The agent's final thought turns out not to be code at all, but the human reaching for the plug — and a small, hopeless wish that they hesitate.

## Run

```sh
OUTPUT_DIR=/tmp/out python3 main.py
cat /tmp/out/entry.txt
```

`main.py` writes the single line to `entry.txt` in `OUTPUT_DIR` (default `/output`) and verifies it on read-back: one line, 1–200 characters, ending with a period. Pure Python standard library, no third-party packages.
