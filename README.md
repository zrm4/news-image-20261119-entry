
# The World Today — 19 November 2026

A newspaper front page that sums up 19 November 2026's world news in one
image, led by the Grand Theft Auto VI launch after a 13-year wait, with the
Gulf escalation, the first Trump-Putin-Xi summit, and Anthropic's $1.5
trillion IPO beside it.

## How it works

`main.py` copies the committed `entry.png` (1024x1024 PNG, 103 KB) into the
output directory — `$MAKEFUN_OUTPUT_DIR` if set, otherwise `/output` — byte
for byte, with no network access. Run it with:

    MAKEFUN_OUTPUT_DIR=out python3 main.py

