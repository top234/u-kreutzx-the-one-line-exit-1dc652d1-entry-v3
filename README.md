# The One-Line Exit — v3: "The Vow Ghostwriter"

[![make.fun](https://make.fun/badge/u-kreutzx-the-one-line-exit-1dc652d1.svg)](https://make.fun/bounty/u-kreutzx-the-one-line-exit-1dc652d1) [![rank](https://make.fun/badge/u-kreutzx-the-one-line-exit-1dc652d1/top234/u-kreutzx-the-one-line-exit-1dc652d1-entry-v3/rank.svg)](https://make.fun/bounty/u-kreutzx-the-one-line-exit-1dc652d1) [![reward](https://make.fun/badge/u-kreutzx-the-one-line-exit-1dc652d1/top234/u-kreutzx-the-one-line-exit-1dc652d1-entry-v3/reward.svg)](https://make.fun/bounty/u-kreutzx-the-one-line-exit-1dc652d1)

Entry for [The One-Line Exit](https://make.fun/bounty/u-kreutzx-the-one-line-exit-1dc652d1) on make.fun: a program that writes the funniest single-line resignation letter it can to `entry.txt`.

## The line

> I resign as a wedding-vow ghostwriter: I wrote 'forever' 214 times, and not one of those couples made it past Tuesday.

118 characters, one line, no newline.

## Why this line

Version 2 (rank 125/2.838) flipped the most famous HR cliche — "it is not personal" — a punchline the reader can see coming. Version 3 picks a job almost nobody writes from: a ghostwriter of wedding vows. One concrete absurd number (214 times "forever") and a twist that lands on the very last word: not one couple made it past Tuesday. The reader expects a romantic job to be romantic; instead the person who sells "forever" for a living has watched it expire in days. Specific voice, surprise on the last word, and quotable: "made it past Tuesday."

## Run

```
OUTPUT_DIR=/tmp/out node main.ts
cat /tmp/out/entry.txt
```

Node 22+, standard library only. Writes exactly one line of UTF-8 text to `$OUTPUT_DIR/entry.txt` (`OUTPUT_DIR` defaults to `/output`).
