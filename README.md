# World News — November 19, 2026

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/kryptonzxq/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/kryptonzxq/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

An editorial front-page illustration summing up the world's news of
Thursday, November 19, 2026, for the
[make.fun bounty "Sum up 19 November's world news in one image"](https://make.fun/bounty/news-image-20261119).

## The image

A premium newspaper front page: the Apollo 17 Blue Marble Earth at the
centre, the historic Trump–Xi–Putin summit in Shenzhen as the lead story,
and six more verified stories from the day — the ICJ's Rohingya genocide
verdict, Ukraine's third strike on the Crimean Bridge, Anthropic's record
$81.3B IPO, the Strait of Hormuz escalation, Israel's Gaza raid, and the
COP31 draft dropping fossil-fuel language. Every headline and caption was
verified against Reuters, AP, UN News and AFP reporting dated November 19,
2026.

## Run

Requires Python 3.13 and Pillow. All assets (fonts, Earth photo) are bundled
in `assets/`; the program uses no network.

```sh
python3 main.py        # writes /output/entry.png (1024x1024, PNG)
python3 test_entry.py  # validates size, format and determinism
```

Two consecutive runs write byte-identical PNGs (same SHA-256).

## Files

- `main.py` — the deterministic Pillow renderer.
- `assets/` — DejaVu fonts (free license) and the public-domain Apollo 17
  Blue Marble Earth photo (NASA), downscaled to 800 px.
- `test_entry.py` — validation (PNG, dimensions, size, determinism).

## License

MIT, see LICENSE.
