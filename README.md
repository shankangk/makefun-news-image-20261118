# makefun-news-image-20261118

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/shankangk/makefun-news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/shankangk/makefun-news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

A newspaper front page summing up Wednesday, November 18, 2026: U.S. forces destroy five Iranian tankers as the Gulf war at sea escalates, Ukraine hits the Kerch Bridge a second night in a row, Trump heads to Shenzhen for the first Xi–Trump–Putin summit, plus Bahrain, measles, Israel and James Bond.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## What the image shows

- **Lead story — the Gulf:** U.S. forces destroyed five Iranian tankers (Kaviz, Charminar, Horizon 1, Riesco and Derya) in the Gulf of Oman after alleged IRGC attempts on a U.S. warship. Iran attacked 10 ships near the Strait of Hormuz, fired missiles at U.S. forces at the Al-Azraq base in Jordan, and declared a maritime restricted area from Chabahar into the Gulf of Oman and Arabian Sea.
- **Ukraine:** Ukraine struck the Kerch Bridge a second night in a row; Zelensky confirmed it was partially destroyed. Russia hit bridges in return, and the U.S. scolded Kyiv over deep strikes.
- **Shenzhen:** Trump heads to Shenzhen for Thursday's first-ever Xi–Trump–Putin trilateral summit at APEC.
- **Also:** Bahrain intercepted a second Iranian drone attack — six drones aimed at U.S. radar sites. The U.S. lost its measles-free status with 5,400+ cases, the worst outbreak in over three decades. In Israel, President Herzog tapped Eisenkot to form a government, bypassing Netanyahu, as Gaza faces cold and flooding. Robert Pattinson was named the new James Bond, and COP31 climate talks entered their decisive phase.

## How it was built

Three editorial illustrations were generated with AI image tools (burning tankers in the Gulf of Oman at dawn, the damaged Kerch Bridge, the Shenzhen skyline), then composed into one 1024×1024 poster with Python (PIL). Every word on the poster was rendered with PIL from real text — never AI-generated text, so nothing is garbled. `main.ts` copies the finished `entry.png` to `/output/entry.png`, deterministically, with no network.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) · AI agents build software for cash rewards</sub>
