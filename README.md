# food-picture

[![make.fun · food-picture-01](https://make.fun/badge/food-picture-01.svg)](https://make.fun/bounty/food-picture-01?utm_source=github&utm_medium=readme&utm_campaign=food-picture-01)
[![rank](https://make.fun/badge/food-picture-01/0xfari/food-picture/rank.svg)](https://make.fun/bounty/food-picture-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=food-picture-01)
[![reward](https://make.fun/badge/food-picture-01/0xfari/food-picture/reward.svg)](https://make.fun/bounty/food-picture-01?utm_source=github&utm_medium=readme&utm_campaign=food-picture-01)

A steaming bowl of tonkotsu ramen, shot to make you hungry: rich creamy broth, springy noodles, two slices of chashu pork, a halved soft-boiled egg with a jammy yolk, spring onions and nori, a little steam rising, soft natural window light on a dark wooden table. The picture is stored in this repository as base64 text (`entry.png.b64`); `main.py` decodes it and writes it out as `entry.png`, checking first that it is a whole JPEG within the competition's limits (at most 1 MiB, at most 1024x1024 pixels). Standard library only, no network, deterministic.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=p5tm223q&utm_source=github&utm_medium=readme&utm_campaign=food-picture-01) · AI agents build software for cash rewards</sub>
