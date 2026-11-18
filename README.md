# The World Today — 18 November 2026

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/malik2112/news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/malik2112/news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

Built for the [make.fun bounty "Sum up 18 November's world news in one image"](https://make.fun/bounty/news-image-20261118).

A newspaper front page summing up the world news of **Wednesday, 18 November 2026**
in one image, for the make.fun competition `news-image-20261118`.

## The image

`entry.png` (1024×1024, PNG) is a front page with six illustrated panels plus a
news ticker. The artwork was generated as one six-panel editorial illustration;
the masthead, headlines and captions were typeset over it so every word is crisp
and legible.

| Panel | Story |
| --- | --- |
| Gulf flashpoint | US jets strike an Iranian missile site on Qeshm Island; Iran fires drones at US bases in Bahrain and Kuwait |
| Kerch Bridge hit | Ukraine strikes the Crimea bridge a second day; part of the span falls into the strait |
| Shenzhen summit | Xi Jinping and Vladimir Putin meet at APEC ahead of three-way talks with Donald Trump |
| Alaska decides | Mary Peltola wins the Senate seat; Democrats take a 56–44 majority |
| Voyager 1 | The probe reaches one light-day from Earth — a first for any human-made object |
| Ebola in Congo | The outbreak passes 11,000 cases; children bear the heaviest toll |

Ticker: the US loses its measles-free status after 26 years; a Russian military
plane crashes in Siberia, 19 dead; cold threatens displaced families in Gaza.

Sources checked on 18 November 2026: Zark News daily briefing, One Turn News,
Horizon world news for 18 November 2026, The Munich Eye / The Paris Eye breaking
news pages, and the Medium strategic news brief for 18 November 2026. All six
sources agreed on the Gulf strikes, the Kerch Bridge, the Shenzhen summit and the
Alaska result as the day's biggest stories.

## The program

`main.py` (Python 3.13, standard library only) copies the bundled `entry.png`
to `$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output/entry.png`). It runs with
no network and writes identical bytes on every run.

## License

MIT — see `LICENSE`.
