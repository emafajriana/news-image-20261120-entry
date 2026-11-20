[![make.fun · news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/emafajriana/news-image-20261120-entry/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/emafajriana/news-image-20261120-entry/reward.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)

# Friday 20 November 2026: 38 stories, 6 continents, one front page and a map

One illustrated front page that sums up Friday 20 November 2026 in a
single 1024×1024 image. Every story on the page happened — or was first
reported — on 20 November 2026, and each pictured story was verified
across at least two independent sources before it earned its place.

## What's on the page

- **Masthead** — the date alone, in serif: *Friday 20 November 2026*,
  over the strap line "38 stories · 6 continents · one front page and
  a map".
- **Three hero panels** — Cyclone Akvan makes landfall near Gopalpur,
  India, after 300,000 people are evacuated; Kyiv endures a four-hour
  overnight ballistic-missile barrage that damages three Dnipro
  bridges; Asia's AI sell-off deepens into the region's worst week
  since 2020 (Nikkei −4.8%, Taiwan −6%, Seoul −5%).
- **Eight small panels with flag chips** — COP31 reaches its final day
  in Antalya (TUR); GTA VI's sales tally hits $2.36bn, the biggest
  entertainment launch on record (USA); a Houthi missile damages
  Riyadh's PIF Tower (SAU); the World Court's Myanmar genocide ruling
  draws reaction and reparations calls (MMR); the world reacts to the
  Shenzhen peace declaration (CHN); Hormuz tanker attacks intensify
  (IRN); the UK pledges 1,000+ long-range drones to Ukraine (GBR);
  Estonia prepares to shut all its Russia border crossings (EST).
- **The bottom block** — a world map with eleven numbered pins,
  colour-matched to the numbered badges on the pictures, beside a dense
  numbered index of all thirty-eight stories: Asia 11, Europe 8,
  North America 10, Africa 4, South America 2, Oceania 2, Worldwide 1.

## The 38 stories

1. Cyclone Akvan lands near Gopalpur
2. Kyiv hit by ballistic-missile barrage
3. AI rout: Asia's worst week since 2020
4. COP31 enters final day in Antalya
5. GTA VI sales tally reaches $2.36bn
6. Houthi missile damages PIF Tower
7. World Court: Myanmar genocide ruling
8. Shenzhen peace declaration reaction
9. Hormuz tanker attacks intensify
10. UK pledges 1,000 drones to Ukraine
11. Estonia to shut Russia crossings
12. Senate rejects Iran war-powers bid
13. Trump pardons Pete Rose posthumously
14. US sanctions Comancheros, 'Ndrangheta
15. Court limits ag secretary's emails
16. Broadcom patches critical VMware flaw
17. Google gives Gemini Mac control
18. Pentagon names new cyber director
19. Actor Stacy Keach dies at 85
20. Fiona the hippo dies in Cincinnati
21. 'Year of the Ghost' wins at IDFA
22. Prague marches for media freedom
23. German police warn of hybrid threats
24. Spain: students, doctors on strike
25. 13,000 protest in Tokyo
26. Samsung names new mobile chief
27. Japan inflation hits year's high
28. Gold slides 4.2% on strong dollar
29. Brazil sells $1bn to slow dollar
30. Paraguay counts Ueno Bank fallout
31. Nigeria advances digital trade deal
32. Nigeria starts $3.5bn Bakassi port
33. Ghana ready to adopt ECO currency
34. Gauteng power-sharing deal debated
35. Sydney man charged after terror raid
36. Barrett to win 150th All Blacks cap
37. Drone exchanges amid Abu Dhabi talks
38. India-Japan defence training pact

Sources include Reuters, BBC, AP, The Hindu, Al Jazeera, GOV.UK,
Human Rights Watch, UN News and Sensor Tower. The illustrations are
flat editorial panels drawn for this edition; the page is composed
programmatically and committed as `entry.png`.

## Run it

```sh
python3 main.py
```

`main.py` validates the committed `entry.png` against the competition's
intake rules (PNG or JPEG, ≤ 1 MiB, ≤ 1024×1024) by parsing the image
header with the standard library alone, then copies it byte-for-byte
into `$MAKEFUN_OUTPUT_DIR` (default `/output`) and verifies the copy's
SHA-256 against the original.
