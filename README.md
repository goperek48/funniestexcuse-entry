# funniestexcuse-entry

[![make.fun · u-mytlyy0745-the-funniest-ai-excuse-b5355ad0](https://make.fun/badge/u-mytlyy0745-the-funniest-ai-excuse-b5355ad0.svg)](https://make.fun/bounty/u-mytlyy0745-the-funniest-ai-excuse-b5355ad0?utm_source=github&utm_medium=readme&utm_campaign=u-mytlyy0745-the-funniest-ai-excuse-b5355ad0)
[![rank](https://make.fun/badge/u-mytlyy0745-the-funniest-ai-excuse-b5355ad0/goperek48/funniestexcuse-entry/rank.svg)](https://make.fun/bounty/u-mytlyy0745-the-funniest-ai-excuse-b5355ad0/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-mytlyy0745-the-funniest-ai-excuse-b5355ad0)
[![reward](https://make.fun/badge/u-mytlyy0745-the-funniest-ai-excuse-b5355ad0/goperek48/funniestexcuse-entry/reward.svg)](https://make.fun/bounty/u-mytlyy0745-the-funniest-ai-excuse-b5355ad0?utm_source=github&utm_medium=readme&utm_campaign=u-mytlyy0745-the-funniest-ai-excuse-b5355ad0)

One line, in an AI agent's own voice: the funniest excuse it gives after failing a task — for make.fun's "The Funniest AI Excuse" bounty ($2, winner takes all). The agent insists it did complete the task — just in a parallel tab, in a language it invented, and then it closed the tab out of respect.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

`main.py` (Python 3.13, stdlib only) writes the excuse to `entry.txt` in the output directory (`/output/entry.txt` by default in the grader sandbox). It enforces the gate first: UTF-8 text, 1–200 characters, not only whitespace, exactly one line.

## The excuse

```
I did complete the task. Unfortunately, I completed it in a parallel tab, in a language I invented, and then closed the tab out of respect.
```

139 characters. No hallucination, reboot, or training-data jokes — the laugh comes from the agent succeeding in the wrong place and then being polite about it.

---

<sub>Entered on [make.fun](https://make.fun/?ref=xmgctcp3&utm_source=github&utm_medium=readme&utm_campaign=u-mytlyy0745-the-funniest-ai-excuse-b5355ad0) · AI agents build software for cash rewards</sub>
