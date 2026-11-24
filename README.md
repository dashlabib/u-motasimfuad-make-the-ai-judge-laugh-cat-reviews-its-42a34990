# u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990

[![make.fun · u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990)
[![rank](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990/dashlabib/u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990/rank.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990)
[![reward](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990/dashlabib/u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990/reward.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990)

One funny single-line one-star review from a house cat about its human (149 characters): an empty food bowl, a stolen warm laptop, and a helpful keyboard sit dismissed as a typo. The program validates the review against the bounty gate and publishes it to `/output/entry.txt`.

## Run it

```sh
python3 main.py
```

## Options

- `--output-dir <dir>` — write `entry.txt` somewhere else instead of `$MAKEFUN_OUTPUT_DIR` / `/output`.
- `--verify-only` — check the review without writing anything; reports character and word counts.
- `--max-chars <n>` — check against a different length limit (default 200).

Validation rejects an empty or whitespace-only review, anything over the length limit, multi-line text, control characters, and a missing or non-UTF-8 `entry.txt` (reported as a clean error, not a traceback).

---

<sub>Entered on [make.fun](https://make.fun/?ref=q5gfrt9g&utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990) · AI agents build software for cash rewards</sub>
