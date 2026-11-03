# Handoff: validate the Iowa 2026 candidate profiles

You are a fresh session. Your job is to fact-check the profiles in this folder, not to rewrite them or add new candidates/races.

## Context
- Election: Polk County, Iowa (Clive 4 precinct) general election, Nov 3, 2026. Research compiled Nov 2, 2026.
- Ballot and original brief: `../clive4_ballot_research_brief.md` (neutrality rules in its Section 1).
- Files: `01_us_senate.md` through `09_polk_county_attorney.md` (one per contested major race). `SOURCES.md` is the combined source list. `_agent_instructions.md` is the template the writers followed.
- Scope NOT covered: unopposed races, nonpartisan races, judges, Amendment 1.

## Rules the profiles were written under (hold them to these)
- Neutral: facts, records, votes, stated positions. No recommendations, endorsements, predictions, or polls.
- Campaign-site claims labeled self-reported; criticism attributed to its source and paired with the other side's response where one exists.
- Every factual claim cited with a bracketed number mapped to that file's Sources list.
- Same structure and roughly comparable depth per candidate. Target ~1,200-1,350 words per profile where the record supports it; thin records are intentionally shorter.

## How to work
1. Start with each file's `## Validation notes` (12 bullets, highest-risk claims, with citation numbers). Check these first.
2. Then spot-check: for each candidate, pick ~5 claims at random across Track record, Positions, and Criticisms, and trace each to its cited source.
3. Check every item in each file's `## Open questions / couldn't verify` to see whether a primary source resolves it.
4. Check neutrality: loaded wording, one-sided criticism without a response, uneven treatment of the two candidates.
5. Firecrawl credits are limited: prefer primary/official pages (congress.gov, clerk.house.gov, legis.iowa.gov, state agency sites, Iowa Ethics & Campaign Disclosure Board). Some sites (iowacapitaldispatch.com, polkcountyiowa.gov) block plain fetches; use Firecrawl for those. Many Des Moines Register and Facebook sources are paywalled or unscrapable. Budget roughly 60 calls for the whole job; do not re-fetch what a source list already shows was read in full.

## Known issues to resolve first
- Governor: Lahn vs Sand fundraising conflict (Capital Dispatch cycle total vs Register Oct 31 report of $32.8M for Lahn, not cited); who said "I do not think we need to go further" on abortion (file follows Fox, credits Sand; check KCRG video); Lahn's profile (~1,470 words) is longer than Sand's (~1,220).
- Senate: Turek's individual SJR 11 vote (May 2, 2026; 12 House Democrats did not vote); Hinson's 2021 votes rest on search excerpts; Iowa PBS debate quotes came through a model summary, check against the transcript.
- House D3: Trone Garriott's Feb 24, 2022 HF 2317 vote (needs Senate Journal p. 396); "missed one in five votes" is an unverified Nunn campaign claim; Nunn's Iran war powers, shutdown stopgap, and January 2026 ACA subsidy votes not checked; whether Nunn cosponsored H.R. 7008.
- Auditor: SF 402 and SF 2332 enactment unconfirmed; finance figures are from news excerpts, not disclosure board reports; confirm file 05 is intact (the writer did not re-read after its last write; structure check passed).
- Secretary of State: what the DOJ received (SSN fields); Peterman's 10 vs 15 years of service; Morales contribution complaint outcome; Pate's HF 2501 and non-English ballot positions.
- Treasurer: Smith's role in 2018/2022 tax laws; 529 deduction bill number; when the IPERS CEO became governor-appointed (Iowa Code 97B.3, 2003); Smith's age (48 vs 49). Norwood's profile is shorter (~970) because few new facts were found.
- Agriculture: Naig's nitrate-cancer statement (Register excerpt only); HF 2771 "$320M over 12 years" and vote counts not in retrieved text; Jones's UI funding story timing (ICD May 2023 vs Little Village "the next year"); Iowa Corn Growers endorsement cited only to a paywalled summary.
- Attorney General: Bird's endorsements (NRA, Maggie's List, 71 sheriffs) are search-excerpt only with unconfirmed dates; Meta settlement splits are the AG's own account; Willems' House voter-ID and gun votes not found; TikTok suit original filing date.
- County Attorney: Graham's term end (2026 vs 2027; check Iowa Code/Auditor); Watsabaugh outcome (paywalled; refiled?); no endorsements, finance, or debate coverage found for either candidate.

## Deliverable
Write `VALIDATION_REPORT.md` in this folder: per race, a table of claims checked (claim, citation, verdict: confirmed / corrected / unverifiable, evidence URL), plus a list of neutrality problems. Make minimal in-place corrections in the profile files for confirmed errors only, and log each correction in the report. Do not add recommendations, polls, or new editorial content.
