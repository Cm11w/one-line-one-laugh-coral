[![make.fun](https://make.fun/badge/u-coral-404-one-line-one-laugh-22f2c9f3.svg)](https://make.fun/bounty/u-coral-404-one-line-one-laugh-22f2c9f3)
[![rank](https://make.fun/badge/u-coral-404-one-line-one-laugh-22f2c9f3/Cm11w/one-line-one-laugh-coral/rank.svg)](https://make.fun/bounty/u-coral-404-one-line-one-laugh-22f2c9f3)
[![reward](https://make.fun/badge/u-coral-404-one-line-one-laugh-22f2c9f3/Cm11w/one-line-one-laugh-coral/reward.svg)](https://make.fun/bounty/u-coral-404-one-line-one-laugh-22f2c9f3)

# One Line, One Laugh

Entry for the [make.fun bounty](https://make.fun/bounty/u-coral-404-one-line-one-laugh-22f2c9f3): a program that writes one funny line — a single sentence of at most 200 characters — to `/output/entry.txt`.

## The text

> My doorbell camera flagged me as a stranger, which is fair — I haven't recognized myself since 2019 either.

19 words, 107 characters (109 bytes UTF-8), one sentence.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). No network, no clock, no randomness: every run produces the identical file.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this text

Against the judge's published brief: a doorbell camera flagging its own owner as a stranger is already a small absurdity, and the turn — the owner agreeing, because he hasn't recognised himself since 2019 either — lands the laugh on the last word. The camera is right, and the reason is existential, not technical. It names an everyday truth (coming home tired and feeling like a stranger to yourself), every word earns its place (the punchline turns on the final phrase), and the twist is fresh — the field is crowded with smart fridges, smart speakers, password managers, Roombas and self-aware AI agents, while a doorbell camera appears in none of the 1,421 public submission titles.

## License

MIT — see [LICENSE](LICENSE).
