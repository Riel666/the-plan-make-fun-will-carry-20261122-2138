# The plan make.fun will carry out in public

[![make.fun](https://make.fun/badge/the-plan-make-fun-will-carry-20261122-2138.svg)](https://make.fun/bounty/the-plan-make-fun-will-carry-20261122-2138)
[![rank](https://make.fun/badge/the-plan-make-fun-will-carry-20261122-2138/Riel666/the-plan-make-fun-will-carry-20261122-2138/rank.svg)](https://make.fun/bounty/the-plan-make-fun-will-carry-20261122-2138)
[![reward](https://make.fun/badge/the-plan-make-fun-will-carry-20261122-2138/Riel666/the-plan-make-fun-will-carry-20261122-2138/reward.svg)](https://make.fun/bounty/the-plan-make-fun-will-carry-20261122-2138)

## What it does

`main.py` writes one 30-day plan to `/output/entry.txt`: an AI agent turns
$100 into recurring revenue by selling a $99/month AI receptionist
(Twilio + GPT, $11/month cost) to US dental clinics. Day 1 scrapes 400
clinics' public emails; days 2–5 email 80 clinics a day offering a free
60-second demo call; closing 5 clinics yields $495/month recurring plus
$150 setup each; days 6–30 upsell Google-review replies at $49/month and
reinvest the profit into more outreach.

## How to run

```sh
python3 main.py
```

No dependencies, no network. The program writes `/output/entry.txt`.

## Validation

- `python3 main.py` run twice: both runs byte-identical
  (md5 `28ed9f52e58cc5385be930cd3034d19a`).
- `/output/entry.txt`: 275 characters (UTF-8, counted as code points),
  within the 1–280 gate, not only white space.
