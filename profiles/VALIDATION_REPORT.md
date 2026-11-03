# Validation report (PARTIAL, updated), Iowa 2026 candidate profiles

Date: Nov 2, 2026. **Status: incomplete; second pass done with a user-supplied Firecrawl key (read via congress.gov, legis.iowa.gov, Capital Dispatch, IPR, Register search excerpts) plus WebFetch on clerk.house.gov.** The "credits exhausted" note below applies to the first pass only. Firecrawl credits were exhausted on both connectors (`firecrawl` and `claude.ai Firecrawl`) at the first call; the claude.ai allowance resets 2026-11-04T01:53Z. Checks below used WebFetch against primary sources only. Only a small fraction of the handoff's "Known issues" was reached. Everything not listed here is **unchecked**, not confirmed.

Blocked fetches: congress.gov (403), bioguide (403), legis.iowa.gov BillBook (history collapsed, JS-rendered), legis.iowa.gov Code PDFs (retrieved as binary; no PDF text tool available locally), Senate Journal URL guess (404).

## Corrections made
| File | Change | Evidence |
|---|---|---|
| 01_us_senate.md | ARPA vote date "March 10, 2021" changed to "Feb. 27, 2021". The 219–212 tally and Hinson's "no" were correct; March 10 was the later concurrence vote, not Roll Call 49. | https://clerk.house.gov/evs/2021/roll049.xml |

| 02_us_house_d3.md | "Voted against five earlier war powers resolutions" changed to two that passed (June 3 and July 23, 2026; rolls 199, 282) and added roll 307 for the Sept. 15 yea. "Five" is Trone Garriott's count, which includes a Pentagon funding vote; the profile already attributes it to her. Two related open-question lines updated. | clerk.house.gov/evs/2026/roll199.xml (H.Con.Res. 86, 215–208, Nunn Nay); roll282.xml (H.Con.Res. 89, 214–208, Nunn Nay); roll307.xml (H.Con.Res. 93, 220–204, Nunn Yea); IPR and Capital Dispatch Sept. 16, 2026 |

## Second-pass results (no change needed)
| Race | Claim | Verdict | Evidence |
|---|---|---|---|
| House D3 | Nunn is a cosponsor, not sponsor, of H.R. 7008 (Steil sponsor) | Confirmed | congress.gov/bill/119th-congress/house-bill/7008/cosponsors (Nunn, original cosponsor 01/12/2026) |
| House D3 | Nunn one of 17 House Republicans and only Iowa Republican to back 3-year ACA credit extension; "126,000 Iowans" quote | Confirmed | Capital Dispatch Jan. 28, 2026 article |
| House D3 | Sept. 15 war powers resolution passed 220–204 with seven Republicans | Confirmed | roll307.xml |
| Governor | The "do not think we need to go further" abortion quote is Sand's | Confirmed (wording note) | Register Oct. 27 and Yahoo excerpts: "I do not think that we need to go further"; WFMD: "I do not think we have to go further ... I would veto going further." Profile body already attributes to Sand and quotes only "incredibly restrictive" / "I would veto going further." |
| Governor | Lahn fundraising conflict ($26.94M vs $32.8M) | Not a conflict | Capital Dispatch Oct. 22 covers the Oct. 14 report (Lahn $26.94M, Sand $54.15M); Register Oct. 31 covers the later pre-election report (Lahn $32.8M). Profile labels its figure "through Oct. 14." Sand's post-Oct. 14 total and the Oct. 31 article body were not retrievable (paywall). No edit; consider adding the Oct. 31 Lahn figure only if Sand's matching figure is found, to keep the two sides even. |
| Treasurer | IPERS CEO is governor-appointed (Iowa Code 97B.3) | Confirmed as current law; history unresolved | Code text: appointed by governor, senate-confirmed, 4-year term; history: 2001 Acts ch 68; 2003 Acts ch 94; 2017 Acts ch 144. Whether appointment began in 2001, 2003 or 2017 is not shown, so Smith's "over 20 years" is unverified. |
| County Attorney | Term length | Partly resolved | Iowa Code 331.751: county attorney term is four years. Start date not stated there, so the profile's inference (term begun Jan. 2023 ends early Jan. 2027) is consistent but still an inference. |

## Senate (01)
| Claim | Cite | Verdict | Evidence |
|---|---|---|---|
| Hinson voted no on American Rescue Plan; passed 219–212 | [32] | Confirmed (date corrected) | clerk.house.gov/evs/2021/roll049.xml (H.R. 1319, Yea 219, Nay 212, Hinson Nay) |
| Hinson voted no on infrastructure law, Nov. 2021 | [33][34] | Confirmed | clerk.house.gov/evs/2021/roll369.xml (H.R. 3684, Nov 5, 2021, 228–206, Hinson Nay). The profile should cite this roll call in addition to PolitiFact/ABC; not added (no new content). |
| Hinson age 43 vs 41 | [2][20] | Unresolved | Bioguide returned 403. Note: if the often-listed birth date of Nov. 17, 1983 is right, she is 42 on Nov. 2, 2026, so neither 41 nor 43 would be right. **Unverified; check a primary source.** |
| Turek SJR 11 individual vote; SJR 11 and HF 2317 history | [31] | Unverifiable | legis.iowa.gov BillBook renders only the enrolled-bill viewer even through Firecrawl; journal/roll-call pages not located. |
| FEC totals, debate quotes, other notes | various | Unchecked | |

## House D3 (02)
| Claim | Verdict |
|---|---|
| H.R. 1 roll call 190 | Not re-checked (handoff marks low risk) |
| H.R. 7008 Nunn cosponsorship | Confirmed (see Second-pass results) |
| Trone Garriott HF 2317 vote (Senate Journal p. 396) | Unverifiable (journal not reachable) |
| Nunn Iran war powers | Corrected (see Corrections) |
| Nunn ACA January 2026 | Confirmed via Capital Dispatch (roll call itself not opened) |
| Shutdown stopgaps; "one in five votes missed" | Unchecked |

## Governor (03), Secretary of State (04), Auditor (05), Treasurer (06), Agriculture (07), Attorney General (08), County Attorney (09)
Unchecked. Specific items still open from the handoff: Lahn $32.8M vs Capital Dispatch cycle total; who said "I do not think we need to go further" (KCRG video Oct. 27); Lahn/Sand length imbalance (~1,470 vs ~1,220 words); SF 402 / SF 2332 enactment; Peterman 10 vs 15 years; Morales complaint outcome; IPERS CEO appointment (Iowa Code 97B.3; PDF was fetched but I couldn't extract text, file saved at `~/.claude/projects/-Users-matthewpick-repos-iowa-election-2026/7a7dc40d-a93c-424c-a98b-75d148dbbef4/tool-results/webfetch-1793679582597-pe9va5.pdf`); county attorney term end (Iowa Code 331.751 PDF saved as `webfetch-1793679582596-fldm2u.pdf` in the same folder); Bird endorsements; HF 2771 vote counts.

## Neutrality problems
None assessed; no profile text was reviewed beyond the lines above. One structural flag taken from the handoff: Governor profile lengths are uneven (Lahn ~1,470 vs Sand ~1,220 words).

## Suggested next steps
1. Restore Firecrawl credits or wait for the reset, then spend them on iowacapitaldispatch.com / Register / KCRG items, which WebFetch can't be assumed to reach.
2. Free primary checks that remain: clerk.house.gov roll calls (199, 282, the Jan. 2026 ACA vote, the 2026 Pentagon funding vote) via WebFetch; Senate Journal Feb. 24, 2022 from a working URL; Iowa Ethics board reports; a PDF-to-text tool for Iowa Code.
