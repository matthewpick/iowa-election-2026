# Validation report (PARTIAL, updated), Iowa 2026 candidate profiles

Date: Nov 2, 2026. **Status: incomplete; second pass done with a user-supplied Firecrawl key (read via congress.gov, legis.iowa.gov, Capital Dispatch, IPR, Register search excerpts) plus WebFetch on clerk.house.gov.** In the first pass Firecrawl credits were exhausted on both connectors (`firecrawl` and `claude.ai Firecrawl`) at the first call; the claude.ai allowance resets 2026-11-04T01:53Z. Pass-one checks used WebFetch only. Only a small fraction of the handoff's "Known issues" was reached. Everything not listed here is **unchecked**, not confirmed.

Blocked in pass one (several since resolved via Firecrawl): congress.gov (403), bioguide (403), legis.iowa.gov BillBook (history collapsed, JS-rendered), legis.iowa.gov Code PDFs (retrieved as binary; no PDF text tool available locally), Senate Journal URL guess (404).

## Corrections made
| File | Change | Evidence |
|---|---|---|
| 01_us_senate.md | ARPA vote date "March 10, 2021" changed to "Feb. 27, 2021". The 219–212 tally and Hinson's "no" were correct; March 10 was the later concurrence vote, not Roll Call 49. | https://clerk.house.gov/evs/2021/roll049.xml |
| 02_us_house_d3.md | "Voted against five earlier war powers resolutions" changed to two that passed (June 3 and July 23, 2026; rolls 199, 282) and added roll 307 for the Sept. 15 yea. "Five" is Trone Garriott's count, which includes a Pentagon funding vote; the profile already attributes it to her. Two related open-question lines updated. | clerk.house.gov/evs/2026/roll199.xml (H.Con.Res. 86, 215–208, Nunn Nay); roll282.xml (H.Con.Res. 89, 214–208, Nunn Nay); roll307.xml (H.Con.Res. 93, 220–204, Nunn Yea); IPR and Capital Dispatch Sept. 16, 2026 |

| 05_auditor.md | SF 402 (2023) and SF 2332 (2024): "could not confirm it was enacted" replaced with "did not become law" (3 spots). | legiscan.com/IA/bill/SF402/2023 (introduced Feb 23, 2023; subcommittee recommended passage Mar 22; no later action, "died in committee"); legiscan.com/IA/bill/SF2332/2023 (introduced Feb 14, 2024; committee-approved, "died in chamber") |

## Third-pass results (Secretary of State, Auditor, Agriculture, Attorney General)
| Race | Claim | Verdict | Evidence |
|---|---|---|---|
| Auditor | SF 402 and SF 2332 | Corrected (above) | LegiScan histories |
| Agriculture | HF 2771 signed June 1, 2026 | Confirmed | legiscan.com/IA/bill/HF2771/2025 ("Signed by Governor. H.J. 1169", 2026-06-01) |
| Agriculture | HF 2771 vote counts (open question) | Resolved, not added to profile | Final House 66–18 and Senate 43–2 on May 2, 2026 (earlier House 65–21, May 1). The "$320M over 12 years" figure is still only IDALS's estimate; not in bill history. |
| Agriculture | Iowa Corn Growers endorsement of Naig | Confirmed by primary source (profile cites a paywalled summary) | iowacorn.org/news/iowa-corn-growers-association-pac-announces-2026-candidate-endorsements/ lists Mike Naig |
| Agriculture | Naig cancer remarks [29] | Unverifiable | Register article returns headline only ("says it's 'dangerous' to blame farmers for Iowa cancer rates"), consistent with profile. |
| Secretary of State | HF 2501 attestation repeal: law, effective July 1 | Law confirmed; effective date not re-checked | LegiScan: House 67–25 (Feb 25), Senate 44–0 (Mar 3), House concurrence 63–29, Senate 31–16 (Apr 15 and 7), signed May 2, 2026 (H.J. 1160). Check which amended version the profile's "took effect July 1" refers to. |
| Secretary of State | Morales contribution complaint | Facts confirmed; outcome still unknown | Register via AOL: complaint filed Oct. 20 by Lara Plecas; Pate returned the money, said Oct. 22 he would amend his report; the Ethics Board had not responded. No Board ruling found. |
| Secretary of State | Data sent to DOJ | Partly resolved | IPR (May 5, 2026): driver's license numbers and partial Social Security numbers. Pate's release says DOJ may demand PII "such as" license and SSN numbers without itemizing. Profile should say "partial" SSNs if it doesn't already. |
| Secretary of State | Peterman 10 vs 15 years | Explained, not contradictory | Campaign about page: "over a decade" as an officer and "fifteen years in uniform," a span that includes the Naval Academy; ICD, Radio Iowa and Telegraph Herald: "10 years as a pilot." Different scopes; wording is unresolved by any source. |
| Attorney General | SF 340 (2009): 93–3 final vote | Confirmed | LegiScan: House passed ayes 93, nays 3, April 24, 2009, H.J. 1805; signed May 21. The H-1712 vote (66 no) was not checked. |
| Attorney General | TikTok ruling Jan. 23, 2026 | Confirmed | Iowa Supreme Court No. 24-1566, filed Jan. 23, 2026, amended Apr. 2, 2026; affirmed denial of motion to dismiss for lack of personal jurisdiction. Original filing date not in opinion text read. |
| Attorney General | Maggie's List endorsement of Bird (2026) | Confirmed | maggieslist.org page quoting The Gazette (also endorsed her in 2022). NRA and sheriff endorsements remain unverified. |
| Attorney General | Bird says Willems "voted against voter ID" | Claim source confirmed; the vote itself still unverified | Radio Iowa Oct. 12, 2026, Register Oct. 10. Willems's roll-call vote not located. |

## Neutrality notes (these four races)
- Length: Secretary of State is uneven, Peterman about 1,747 words vs Pate about 1,348. Other races are within roughly 10%: Auditor 1,204/1,241, Agriculture 1,110/1,278, Attorney General 1,295/1,162. Not edited (cutting or adding content is out of scope).
- Loaded wording ("radical," "far-left," "corruption") appears only inside attributed quotations or source titles, each labeled with its speaker; no change needed.
- Not reviewed line by line: whether every criticism has its response.

## Fourth-pass results (Governor, Treasurer)
Corrections to profiles: **03_governor.md**: replaced a placeholder citation ("headline-level only [search result]") on the Wulf $275,000 claim with the KCCI Oct. 22 report (new [36]), keeping Wulf's response. **06_treasurer.md**: added Smith's confirmed yes votes on SF 2417 (2018) and HF 2317 (2022) (new [34][35]) and the SF 418 enactment date (new [36]).
| Race | Claim | Verdict | Evidence |
|---|---|---|---|
| Governor | HF 2104 House vote 64–28, Jan. 21, 2026 | Confirmed | legiscan.com/IA/bill/HF2104/2025 (House passed 64–28; Senate Commerce report 13–5 Jan. 28; died in chamber) |
| Governor | Q3 fundraising figures (Sand $16.31M raised, $28.9M spent, $5.35M cash, DGA $5.5M; Lahn $16.87M, $17.5M, ~$403K cash, $2.5M loans, RGA PAC $11.8M) | Confirmed | IPR Oct. 20, 2026, citing Ethics Board summaries |
| Governor | Lahn $26.94M vs $32.8M | Consistent, not a conflict | $26.94M (Oct. 14 report, ICD) + $5.9M (pre-election report, Register Oct. 31 snippet) = $32.8M. Sand's post-Oct. 14 figure not retrievable (Register paywall); the profile's Sand total is also through Oct. 14. A multistate.us page lists Sand at $37.8M, which conflicts with the $54.15M cycle total and is unexplained; the sum of Sand's reports in the profile ($9.57M + $9.39M + $16.31M = $35.27M) plus 2025 reports could reach $54.15M, but the 2025 figure was not checked. **Unresolved: check Sand's 2025 reports on the Ethics Board site.** |
| Governor | Wulf $275,000 claim | Confirmed and now cited | KCCI Oct. 22: petition filed in Black Hawk County by Wulf's parents (Duane and Jackie Wulf) |
| Governor | Black Hawk County review after Sept. 22 | Unresolved | No charges or dismissal found |
| Governor | Lahn bought Belle Plaine farm 2013 vs 2014 | Weight of sources favors 2014; profile left as is | Modbee/McClatchy and Iowa Democrats (partisan) say 2014 (moved back 2013, bought farmhouse 2014); Kansas Reflector says 2014; KMAland says 2013 |
| Governor | Sand abortion quote | Confirmed in pass two | |
| Governor | Profile length imbalance (Lahn ~1,470 vs Sand ~1,220) | Not changed | Trimming or adding content is out of scope; flagged for the editor |
| Treasurer | Smith's role in 2018 and 2022 tax laws | Partly resolved | Voted yes on SF 2417 (Senate 28–20; signed May 30, 2018) and HF 2317 (Senate 32–16, Feb. 24, 2022); HF 2317 is a committee bill. Floor-manager role not shown. |
| Treasurer | SF 418 enactment | Resolved | Signed May 3, 2023 (House 95–0, Senate 49–1 on Mar. 22) |
| Treasurer | 529 deduction $3,800 to $6,100 | Unverifiable | ISave 529 and Treasurer pages confirm $6,100 for 2026 and $5,800 for 2025; no bill number found. The annual rise suggests inflation indexing, which was not verified. The profile attributes the claim to Smith. |
| Treasurer | Smith age 48 vs 49 | Unresolved | Wikipedia: born 1977, no day, consistent with either |
| Treasurer | IPERS CEO governor-appointed | See pass two | Code 97B.3 history: 2001, 2003, 2017 amendments |
| Treasurer | Norwood record; TBL Ventures | Unchecked | |

## Fifth-pass results (parallel agents: fundraising, neutrality, endorsements, County Attorney)
**Fundraising**
| Claim | Verdict | Evidence |
|---|---|---|
| Sand cycle total $54.15M (through Oct. 14) | Confirmed; the $37.8M on multistate.us is Sand's total through July 14 (stale) | Little Village: Sand $54,149,727, Lahn $26,941,749; Lahn's Ethics Board summary matches ($16,871,785 raised, $403,181 cash, $2.5M loans) |
| Laehn receipts | **Corrected** in 01: $0.08M to $0.06M | FEC candidate S6IA00181: $61,146 through Oct. 14 (new source [39] in 01) |
| Oct. 31 pre-election totals | Added to 03 with labels | Lahn +$5.9M, cycle $32.8M (Register excerpt); Sand's $4.8M raised Oct. 15 to 27 is his campaign's own figure; the Register's "about $59M" is an excerpt. Sand's own Ethics Board report (4,500+ pages) was not read, and the profile's period figures do not sum to the cycle total on their own. |

**Endorsements and attendance (08, 02)**
- Trump endorsement of Bird: Sept. 1, 2026 (CBS2 Iowa). NRA: NRA PVF page marks Bird endorsed, undated. 71 sheriffs: announced in 2022, not 2026 (Gazette Sept. 9, 2022; KTIV Oct. 18, 2022); profile corrected. Willems's list matches his endorsements page; DAGA endorsement confirmed May 6, 2026.
- Willems voter-ID vote: not located (served 2009 to 2013; 2017's HF 516 is not his vote). Bird's claim still rests on campaign and debate reporting.
- "Missed one in five votes": only Nunn campaign posts; no independent record. Profile already labels it a campaign claim.
- Outside spending: Ballotpedia's $3.7M is the sum of two "against" lines, not total spending; OpenSecrets shows about $25.5M involving the two candidates. Totals differ by method and date; profile's attributed "$10.6M" line left as is.

**County Attorney (09), first validation**: Graham's 2022 and 2026 primary results, the April 2026 clinic killing coverage and quotes, Brown's 58-year sentence, Dyer's biography (self-reported) and his nomination at a special convention all confirmed. Term end: Iowa Code 39.17(2) and 331.751(3) put elections in 2022, 2026 and every four years, four-year terms, consistent with the profile's inference of an early-January 2027 end. One small gap: the profile says "two judges" had access to criminal histories, but the article says "the judge." Watsabaugh refiling not found.

**Neutrality fixes (wording only; no content added or trimmed)**
- 02: split merged bullets; removed editorial "though"; neutralized the HF 2317 sentence (profile no longer endorses the Iowa GOP's claim, just records the no vote); Nunn's abortion row now uses his own label.
- 03: removed an unsupported sentence with a placeholder citation; minimum-wage table row now matches body text.
- 04: labeled Pate's "third-generation" self-reported; removed a writer inference about "referee"; removed duplicated Peterman text; SAVE row now says "December 2025 settlement" instead of implying a court win.
- 06: removed "only" from a fact-check sentence. 07: "Helped champion it" replaced with a sourced statement; split merged bullets. 09: replaced unattributed speculation with the fact and Dyer's own words.
- 01 and 05: no violations found. 08: no wording changes.
- Left alone: Lahn/Sand length gap (about 1,476 vs 1,225 words); Laehn has no criticisms and a shorter profile (about 850 words), which reflects coverage; Norwood (972) vs Smith (1,224) per the handoff; Hegseth entry in 02 is about 170 words versus shorter siblings; three nonstandard inline cites and a garbled Muhlbauer phrase in 03; 05 has a "Party support" bullet for Cournoyer with no matching bullet for Wettach.
- Open check: 08 says Bird "lost the 2010 AG race to Miller." Capital Dispatch says so, but Ballotpedia's 2010 page names the nominee "Findley," and a name change was not confirmed.

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
| Hinson age 43 vs 41 | [2][20] | Corrected in report: 43 stands | Wikipedia lists birth date June 27, 1983 (age 43 on Nov. 2, 2026); ICD's 41 appears wrong. Bioguide was not reachable, so this is secondary-sourced. (Pass-one speculation about a Nov. 17 birth date was wrong and is withdrawn.) |
| Turek SJR 11 and HJR 2006 individual votes | [23][31] | Resolved (profile updated) | LegiScan roll calls (rawHtml): SJR 11 final passage, House, May 2, 2026 (57–21, 22 absent): Turek **absent**; HJR 2006, House, Mar. 26, 2024 (61–35): Turek **Nay**. https://legiscan.com/IA/rollcall/SJR11/id/1693487 ; https://legiscan.com/IA/rollcall/HJR2006/id/1426842. Added as [37][38] in file 01. Note: Hinson's campaign claims he "voted against advancing" Amendment 1 [22]; the profile now says the final-passage record shows absent and that amendment votes were not checked. |
| FEC totals (Hinson $14.15M, Turek $24.29M) | [3] | Confirmed | openFEC totals through 2026-10-14: Hinson $14,147,973 receipts (includes $3.91M transfers from her other authorized committee, so the "may include transfers" caveat is justified); Turek $24,290,521 (includes $1.56M transfers). |
| Laehn receipts $0.08M | [3] | **Discrepancy, not edited** | openFEC shows Laehn (S6IA00181) receipts of $61,146 through 2026-10-14, about $0.06M, not $0.08M. The profile cites Ballotpedia for the figure; recommend replacing with FEC or removing. |
| Iowa PBS debate quotes ("gaming the system," "dangerous criminal illegals," "bad trade partners," "up to 15 times more wealthy," "orderly end," $5M stock) | [11] | Confirmed | All appear in the Iowa PBS transcript (fetched in full); speaker attribution checked for the Turek wealth claim, Hinson's "orderly end" and stock-sale reply, and the work-requirements quote. |
| Missed votes: Hinson 5 of 283 (1.1%); Turek 58.1%; Turek 81% career (his campaign) | [12] | Confirmed | KTIV Aug. 26, 2026 article states each figure and labels 81% as Turek's campaign claim. |
| Hinson's farm bill, E15, ACA votes; IPR border-bill statement | [9][14][15][25] | Unchecked | |

## House D3 (02)
| Claim | Verdict |
|---|---|
| H.R. 1 roll call 190 | Not re-checked (handoff marks low risk) |
| H.R. 7008 Nunn cosponsorship | Confirmed (see Second-pass results) |
| Trone Garriott HF 2317 vote | Confirmed: Nay, Senate passed 32–16 on Feb. 24, 2022 (LegiScan roll call id 1154700; open-question lines updated) |
| FEC totals (Nunn $6.12M raised/$5.56M spent/$620,759 on hand; Trone Garriott $8.07M/$6.92M/$1.15M) | Confirmed against openFEC through 2026-10-14 |
| Hatch Act complaint (filed Sept. 11) | Filing confirmed (Capital Dispatch, KCRG, DCCC); no OSC decision found |
| Nunn Iran war powers | Corrected (see Corrections) |
| Nunn ACA January 2026 | Confirmed via Capital Dispatch (roll call itself not opened) |
| Nunn campaign: Trone Garriott "missed one in five votes"; shutdown stopgaps; outside-spending discrepancy ($10.6M vs $3.7M) | Unchecked (no aggregate attendance source reachable) |

## Governor (03), Secretary of State (04), Auditor (05), Treasurer (06), Agriculture (07), Attorney General (08), County Attorney (09)
Mostly unchecked (see Second-pass results for Governor, Treasurer and County Attorney items). Still open from the handoff: Sand's post-Oct. 14 fundraising total; Lahn/Sand length imbalance (~1,470 vs ~1,220 words); SF 402 / SF 2332 enactment; Peterman 10 vs 15 years; Morales complaint outcome; Bird endorsements; HF 2771 vote counts.

## Neutrality problems
None assessed; no profile text was reviewed beyond the lines above. One structural flag taken from the handoff: Governor profile lengths are uneven (Lahn ~1,470 vs Sand ~1,220 words).

## Suggested next steps
1. Restore Firecrawl credits or wait for the reset, then spend them on iowacapitaldispatch.com / Register / KCRG items, which WebFetch can't be assumed to reach.
2. Free primary checks that remain: clerk.house.gov roll calls (199, 282, the Jan. 2026 ACA vote, the 2026 Pentagon funding vote) via WebFetch; Senate Journal Feb. 24, 2022 from a working URL; Iowa Ethics board reports; a PDF-to-text tool for Iowa Code.
