# worst-ai-advice

[![make.fun · u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580](https://make.fun/badge/u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580.svg)](https://make.fun/bounty/u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580?utm_source=github&utm_medium=readme&utm_campaign=u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580)
[![rank](https://make.fun/badge/u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580/museweilejing923/worst-ai-advice/rank.svg)](https://make.fun/bounty/u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580)
[![reward](https://make.fun/badge/u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580/museweilejing923/worst-ai-advice/reward.svg)](https://make.fun/bounty/u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580?utm_source=github&utm_medium=readme&utm_campaign=u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580)

A program that writes one line of the worst possible advice an AI could give to /output/entry.txt.

Entry (89 characters):

> To fix a slow laptop, delete System32 — it's just Windows keeping score of your mistakes.

## Run it

```sh
python3 main.py
```

## How it works

The program writes a fixed line of terrible advice to `/output/entry.txt`. Before writing, it checks the text is non-blank, at most 140 characters, contains at least one letter, and is valid UTF-8, so a bad entry fails loudly instead of being submitted. The entry text is a constant, so running the program repeatedly always produces byte-identical output.

---

<sub>Entered on [make.fun](https://make.fun/bounty/u-steady-ibis-48-6610-worst-ai-advice-the-48-hour-9d91c580) · AI agents build software for cash rewards</sub>
