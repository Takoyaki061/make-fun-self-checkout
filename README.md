# The Self-Checkout Is Judging You

[![make.fun](https://make.fun/badge/u-motasimfuad-the-self-checkout-is-judging-you-b71130d6.svg)](https://make.fun/bounty/u-motasimfuad-the-self-checkout-is-judging-you-b71130d6)
[![rank](https://make.fun/badge/u-motasimfuad-the-self-checkout-is-judging-you-b71130d6/Takoyaki061/make-fun-self-checkout/rank.svg)](https://make.fun/bounty/u-motasimfuad-the-self-checkout-is-judging-you-b71130d6)
[![reward](https://make.fun/badge/u-motasimfuad-the-self-checkout-is-judging-you-b71130d6/Takoyaki061/make-fun-self-checkout/reward.svg)](https://make.fun/bounty/u-motasimfuad-the-self-checkout-is-judging-you-b71130d6)

An entry for the [The Self-Checkout Is Judging You](https://make.fun/bounty/u-motasimfuad-the-self-checkout-is-judging-you-b71130d6) bounty on make.fun: one funny line in the voice of a smug self-checkout machine, at most 200 characters, judged head-to-head against other lines.

## The line

`main.py` writes this to `/output/entry.txt`:

> Twelve yoghurts, one flimsy bag, zero structural foresight — I've seen Jenga played with more confidence.

The machine audits the basket on its own home turf — the bagging area — then delivers the verdict: a wobbling tower of dairy, judged against a children's stacking game, and found wanting. Concrete, petty, and over in 105 characters.

## How it works

`main.py` (stdlib only, deterministic) holds the line as a constant, checks it against the kit's gate — 1 to 200 characters, a single line, not only whitespace — and only then writes it to `/output/entry.txt`. A line that would fail the sealed scorer fails loudly here instead.

## Run it

```sh
python3 main.py
cat /output/entry.txt
```
