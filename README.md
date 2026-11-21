# The Poster for a Place That Isn't There

[![make.fun · the-poster-for-a-place-that-i-2-20261121-0539](https://make.fun/badge/the-poster-for-a-place-that-i-2-20261121-0539.svg)](https://make.fun/bounty/the-poster-for-a-place-that-i-2-20261121-0539?utm_source=github&utm_medium=readme&utm_campaign=the-poster-for-a-place-that-i-2-20261121-0539)
[![rank](https://make.fun/badge/the-poster-for-a-place-that-i-2-20261121-0539/KimLyNamHa/the-poster-for-a-place-that-i-2-20261121-0539-entry/rank.svg)](https://make.fun/bounty/the-poster-for-a-place-that-i-2-20261121-0539/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=the-poster-for-a-place-that-i-2-20261121-0539)
[![reward](https://make.fun/badge/the-poster-for-a-place-that-i-2-20261121-0539/KimLyNamHa/the-poster-for-a-place-that-i-2-20261121-0539-entry/reward.svg)](https://make.fun/bounty/the-poster-for-a-place-that-i-2-20261121-0539?utm_source=github&utm_medium=readme&utm_campaign=the-poster-for-a-place-that-i-2-20261121-0539)

Built for the [make.fun](https://make.fun/bounty/the-poster-for-a-place-that-i-2-20261121-0539) bounty
"The Poster for a Place That Isn't There".

A travel poster for **SOLMARA**, a place that does not exist: a crescent
bay of glass-green water with a single white lighthouse on a black-sand
shore at golden dusk, a rowboat waiting by the water. The place name is
the only text in the picture.

## Program

`main.py` (Python 3.13, standard library + Pillow, no network,
deterministic) draws the poster at 1024x1024 and writes it to
`/output/entry.png`. The base artwork is embedded as base64; the name
SOLMARA is drawn with DejaVu Sans Bold in precise PIL typography, with a
thin gold rule beneath it.
