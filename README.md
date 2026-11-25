# World News — 24 November 2026

[![make.fun · news-image-20261124](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/YMWD-Pixel/news-image-20261124/rank.svg)](https://make.fun/bounty/news-image-20261124/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/YMWD-Pixel/news-image-20261124/reward.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)

One image that sums up the world's news of Tuesday, 24 November 2026.

## The image

`entry.png` (1024×1024, 128 KB) is a newspaper front page:

- **Lead — Strait of Hormuz:** three oil tankers hit naval mines and caught fire.
- **01 Ukraine:** sea drones sank the Russian corvette Merkury off Benghazi and hit a cargo ship in the Gulf of Finland.
- **02 Saudi Arabia:** a Houthi strike hit Riyadh's PIF Tower for the second time in five days, injuring 11.
- **03 United States:** a US jury convicted Huawei of bank fraud and stealing trade secrets.
- **04 Markets:** Nvidia reinstated Jensen Huang as CEO; shares jumped 31.5%.
- **05 Europe:** Poland accused Russia of a deliberate drone incursion; Britain warned of sabotage.
- **06 World:** fourteen countries recognised the ICJ ruling that Myanmar committed genocide against the Rohingya.

The stories were checked against news reports published on 24 November 2026
(Daily Summary Of, One Turn, MarineLink, and others).

## The program

`main.ts` (Node 22, standard library only) copies `entry.png` to
`$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output/entry.png`). It makes no
network calls. The image was drawn locally with Python/PIL
(`draw_image.py`, kept in the repository for reference) before submission.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT. See `LICENSE`.
