# the-vault-gallery — deploy note
Target: github.com/mkazigwaa-max/the-vault-gallery (Pages, root)
Serves at: https://mkazigwaa-max.github.io/the-vault-gallery/
Tree: index.html (self-contained; DATA inline) + media/ + assets/.
Cross-links point at the newsstand (separate repo, untouched).

## Deploy encode policy (owner ruling 2026-10-27 05:54 CT — choice delegated)
Local masters in paintings-gallery/media/ stay LAW-PURE (untouched).
Deploy copies below are web encodes: native pixel dimensions kept
wherever the file lands under GitHub's 100 MB/file cap at q90
(fallback q88), 4:2:2. Only the giants that still exceed the cap
have their DEPLOY COPY's dimensions reduced to the largest size
fitting under ~95 MB — still far above 4K. Deep zoom on the live
site reads these deploy copies (same relative paths); the local
build keeps pointing at the pure masters.

Deploy tree total: 619.8 MB (budget < ~950 MB) — WITHIN BUDGET.
Files encoded: 56. Copies reduced in dimensions: 2.

| file | native dims | deploy dims | master bytes | deploy bytes | note |
|---|---|---|---|---|---|
| 01-full.jpg | 8242x5640 | 8242x5640 | 17031011 | 12553051 | native dims, q90 |
| 01-hero.jpg | 3840x2159 | 3840x2159 | 2641840 | 2754407 | native dims, q90 |
| 02-full.jpg | 22284x17646 | 15303x12118 | 258729366 | 90637292 | deploy copy reduced to fit ~95 MB, q90 (native dims exceed cap) |
| 02-hero.jpg | 3840x2159 | 3840x2159 | 3813370 | 3957623 | native dims, q90 |
| 03-full.jpg | 14168x11528 | 14168x11528 | 85194552 | 58512750 | native dims, q90 |
| 03-hero.jpg | 3840x2159 | 3840x2159 | 2506728 | 2603855 | native dims, q90 |
| 04-full.jpg | 4826x5548 | 4826x5548 | 13319677 | 9086281 | native dims, q90 |
| 04-hero.jpg | 3840x2159 | 3840x2159 | 2651461 | 2821294 | native dims, q90 |
| 05-full.jpg | 9360x5581 | 9360x5581 | 24348123 | 17518258 | native dims, q90 |
| 05-hero.jpg | 3840x2160 | 3840x2160 | 2546998 | 2633474 | native dims, q90 |
| 06-full.jpg | 6232x7880 | 6232x7880 | 17082813 | 12694268 | native dims, q90 |
| 06-hero.jpg | 3840x2159 | 3840x2159 | 2123495 | 2246417 | native dims, q90 |
| 07-full.jpg | 5256x6742 | 5256x6742 | 20146372 | 14298727 | native dims, q90 |
| 07-hero.jpg | 3840x2159 | 3840x2159 | 3299578 | 3385112 | native dims, q90 |
| 08-full.jpg | 30000x19970 | 15000x9985 | 399462501 | 84013114 | 1/2 DCT draft decode (full decode OOM on this box), q90 |
| 08-hero.jpg | 3840x2159 | 3840x2159 | 3250028 | 3410554 | native dims, q90 |
| 09-full.jpg | 12285x14550 | 12285x14550 | 51121713 | 37803843 | native dims, q90 |
| 09-hero.jpg | 3840x2159 | 3840x2159 | 2592086 | 2676302 | native dims, q90 |
| 10-full.jpg | 7376x7401 | 7376x7401 | 42961069 | 30249352 | native dims, q90 |
| 10-hero.jpg | 3840x2160 | 3840x2160 | 4459844 | 4571649 | native dims, q90 |
| 11-full.jpg | 5872x4008 | 5872x4008 | 14402597 | 10196960 | native dims, q90 |
| 11-hero.jpg | 3840x2160 | 3840x2160 | 3439533 | 3536187 | native dims, q90 |
| 12-full.jpg | 2287x4200 | 2287x4200 | 7023859 | 4355243 | native dims, q90 |
| 12-hero.jpg | 2287x1286 | 2287x1286 | 1315117 | 1343375 | native dims, q90 |
| 13-full.jpg | 5922x7329 | 5922x7329 | 14153551 | 9931443 | native dims, q90 |
| 13-hero.jpg | 3840x2159 | 3840x2159 | 2837277 | 2934038 | native dims, q90 |
| 14-full.jpg | 4608x3456 | 4608x3456 | 3985650 | 2918994 | native dims, q90 |
| 14-hero.jpg | 3840x2160 | 3840x2160 | 1439470 | 1471222 | native dims, q90 |
| 15-full.jpg | 7675x4325 | 7675x4325 | 18401731 | 13652638 | native dims, q90 |
| 15-hero.jpg | 3840x2159 | 3840x2159 | 3472639 | 3607364 | native dims, q90 |
| 16-full.jpg | 7087x4820 | 7087x4820 | 12219449 | 8579527 | native dims, q90 |
| 16-hero.jpg | 3840x2159 | 3840x2159 | 3214839 | 3344084 | native dims, q90 |
| 17-full.jpg | 3036x4416 | 3036x4416 | 7814867 | 5494257 | native dims, q90 |
| 17-hero.jpg | 3036x1707 | 3036x1707 | 2379624 | 2414868 | native dims, q90 |
| 18-full.jpg | 5684x4223 | 5684x4223 | 8917435 | 6088329 | native dims, q90 |
| 18-hero.jpg | 3840x2159 | 3840x2159 | 2033777 | 2101031 | native dims, q90 |
| 19-full.jpg | 6162x4226 | 6162x4226 | 8019198 | 5218050 | native dims, q90 |
| 19-hero.jpg | 3840x2159 | 3840x2159 | 2120629 | 2178588 | native dims, q90 |
| 20-full.jpg | 5773x4478 | 5773x4478 | 9028455 | 6012926 | native dims, q90 |
| 20-hero.jpg | 3840x2159 | 3840x2159 | 2711887 | 2780633 | native dims, q90 |
| 21-full.jpg | 4200x3205 | 4200x3205 | 6563732 | 4332637 | native dims, q90 |
| 21-hero.jpg | 3840x2159 | 3840x2159 | 2420180 | 2494473 | native dims, q90 |
| 22-full.jpg | 7479x11146 | 7479x11146 | 59766049 | 41147589 | native dims, q90 |
| 22-hero.jpg | 3840x2159 | 3840x2159 | 4049168 | 4170830 | native dims, q90 |
| 23-full.jpg | 4521x4183 | 4521x4183 | 4899279 | 3597195 | native dims, q90 |
| 23-hero.jpg | 3840x2159 | 3840x2159 | 1491487 | 1580910 | native dims, q90 |
| 24-full.jpg | 8192x6577 | 8192x6577 | 27000055 | 18746788 | native dims, q90 |
| 24-hero.jpg | 3840x2160 | 3840x2160 | 2863799 | 2906721 | native dims, q90 |
| 25-full.jpg | 4045x5205 | 4045x5205 | 10920743 | 7477639 | native dims, q90 |
| 25-hero.jpg | 3840x2159 | 3840x2159 | 2691977 | 2775068 | native dims, q90 |
| 26-full.jpg | 4737x6118 | 4737x6118 | 5966824 | 4051139 | native dims, q90 |
| 26-hero.jpg | 3840x2159 | 3840x2159 | 1528844 | 1579360 | native dims, q90 |
| 27-full.jpg | 6433x8667 | 6433x8667 | 24087660 | 17297191 | native dims, q90 |
| 27-hero.jpg | 3840x2159 | 3840x2159 | 2278336 | 2349421 | native dims, q90 |
| 28-full.jpg | 5184x3888 | 5184x3888 | 8393003 | 6001733 | native dims, q90 |
| 28-hero.jpg | 3840x2160 | 3840x2160 | 2357849 | 2442691 | native dims, q90 |

Standing notes:
- media/02-full.jpg (Starry Night): the LOCAL master itself is a
  1/2 draft decode (22,284x17,646) of the 44,567x35,291 original —
  native decode OOMs on this box (named gap in BUILD-LOG.md).
- Local masters 12-full and 21-full were upscaled per the
  enhancement law (sub-4K sources); all other masters are exact
  native. Deploy copies inherit master dimensions unless the
  cap forced a reduction, per the table above.
