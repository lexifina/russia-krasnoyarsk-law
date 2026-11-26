<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Krasnoyarsk Krai only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-26 05:38 UTC, Krasnoyarsk Krai: Official Internet Portal of Legal Information (region24): 13 addresses read; 0 added, 0 changed, 0 removed; no change; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Krasnoyarsk Krai: Official Internet Portal of Legal Information (region24)](http://publication.pravo.gov.ru/documents/block/region24) | `zakony-<year>/` | daily | 2026-11-26 05:38 UTC | no change | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-26 05:37](checks/2026-11.md#ru-pravo-krasnoyarsk-20261126t053719z) | pravo-krasnoyarsk | 13 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-25 06:10](checks/2026-11.md#ru-pravo-krasnoyarsk-20261125t061014z) | pravo-krasnoyarsk | 13 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-24 14:04](checks/2026-11.md#ru-pravo-krasnoyarsk-20261124t140450z) | pravo-krasnoyarsk | 13 | 6 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-krasnoyarsk-law/compare/61e13bc7074b...6d6325ddc33e) |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
