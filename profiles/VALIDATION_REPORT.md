# Validation report (PARTIAL), Iowa 2026 candidate profiles

Date: Nov 2, 2026. **Status: incomplete.** Firecrawl credits were exhausted on both connectors (`firecrawl` and `claude.ai Firecrawl`) at the first call; the claude.ai allowance resets 2026-11-04T01:53Z. Checks below used WebFetch against primary sources only. Only a small fraction of the handoff's "Known issues" was reached. Everything not listed here is **unchecked**, not confirmed.

Blocked fetches: congress.gov (403), bioguide (403), legis.iowa.gov BillBook (history collapsed, JS-rendered), legis.iowa.gov Code PDFs (retrieved as binary; no PDF text tool available locally), Senate Journal URL guess (404).

## Corrections made
| File | Change | Evidence |
|---|---|---|
| 01_us_senate.md | ARPA vote date "March 10, 2021" changed to "Feb. 27, 2021". The 219–212 tally and Hinson's "no" were correct; March 10 was the later concurrence vote, not Roll Call 49. | https://clerk.house.gov/evs/2021/roll049.xml |

## Senate (01)
| Claim | Cite | Verdict | Evidence |
|---|---|---|---|
| Hinson voted no on American Rescue Plan; passed 219–212 | [32] | Confirmed (date corrected) | clerk.house.gov/evs/2021/roll049.xml (H.R. 1319, Yea 219, Nay 212, Hinson Nay) |
| Hinson voted no on infrastructure law, Nov. 2021 | [33][34] | Confirmed | clerk.house.gov/evs/2021/roll369.xml (H.R. 3684, Nov 5, 2021, 228–206, Hinson Nay). The profile should cite this roll call in addition to PolitiFact/ABC; not added (no new content). |
| Hinson age 43 vs 41 | [2][20] | Unresolved | Bioguide returned 403. Note: if the often-listed birth date of Nov. 17, 1983 is right, she is 42 on Nov. 2, 2026, so neither 41 nor 43 would be right. **Unverified; check a primary source.** |
| Turek SJR 11 individual vote; SJR 11 and HF 2317 history | [31] | Unverifiable here | legis.iowa.gov history is collapsed/JS-rendered. |
| FEC totals, debate quotes, other notes | various | Unchecked | |

## House D3 (02)
| Claim | Verdict |
|---|---|
| H.R. 1 roll call 190 | Not re-checked (handoff marks low risk) |
| H.R. 7008 Nunn cosponsorship | Unverifiable (congress.gov 403) |
| Trone Garriott HF 2317 vote (Senate Journal p. 396) | Unverifiable (journal not reachable) |
| Nunn Iran war powers, ACA January 2026, shutdown stopgaps; "one in five votes missed" | Unchecked |

## Governor (03), Secretary of State (04), Auditor (05), Treasurer (06), Agriculture (07), Attorney General (08), County Attorney (09)
Unchecked. Specific items still open from the handoff: Lahn $32.8M vs Capital Dispatch cycle total; who said "I do not think we need to go further" (KCRG video Oct. 27); Lahn/Sand length imbalance (~1,470 vs ~1,220 words); SF 402 / SF 2332 enactment; Peterman 10 vs 15 years; Morales complaint outcome; IPERS CEO appointment (Iowa Code 97B.3; PDF was fetched but I couldn't extract text, file saved at `~/.claude/projects/-Users-matthewpick-repos-iowa-election-2026/7a7dc40d-a93c-424c-a98b-75d148dbbef4/tool-results/webfetch-1793679582597-pe9va5.pdf`); county attorney term end (Iowa Code 331.751 PDF saved as `webfetch-1793679582596-fldm2u.pdf` in the same folder); Bird endorsements; HF 2771 vote counts.

## Neutrality problems
None assessed; no profile text was reviewed beyond the lines above. One structural flag taken from the handoff: Governor profile lengths are uneven (Lahn ~1,470 vs Sand ~1,220 words).

## Suggested next steps
1. Restore Firecrawl credits or wait for the reset, then spend them on iowacapitaldispatch.com / Register / KCRG items, which WebFetch can't be assumed to reach.
2. Free primary checks that remain: clerk.house.gov roll calls (199, 282, the Jan. 2026 ACA vote, the 2026 Pentagon funding vote) via WebFetch; Senate Journal Feb. 24, 2022 from a working URL; Iowa Ethics board reports; a PDF-to-text tool for Iowa Code.
