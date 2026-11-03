# Clive 4 Ballot Research Brief (Polk County, Iowa – General Election, Nov 3, 2026)

Handoff file for a Claude Code session. Compiled Nov 2, 2026 from a claude.ai chat.
Goal: fan out one research task per race and produce a neutral, side-by-side comparison for each choice.

---

## 1. Instructions for the Claude Code session

**Task.** Run one research subtask per race in Section 4. Within each race, give every candidate the same treatment: the same questions, the same depth, and the same source types.

**Neutrality rules**
- Report facts: background, record, votes, and the candidate's own stated positions.
- Do not make recommendations, endorsements, or predictions.
- Do not include polls or "who will win" analysis.
- Attribute any criticism to whoever made it. Pair it with the response from the other side where one exists.
- For ballot measures, give the strongest case from supporters and from opponents, with equal length.

**Source hierarchy (use in this order)**
1. Official government sources: Polk County Auditor, Iowa Secretary of State, Iowa Legislature (legis.iowa.gov), Iowa Judicial Branch (iowacourts.gov).
2. Nonpartisan news and voter guides: Iowa Capital Dispatch, Des Moines Register, Iowa Public Radio, The Gazette, Radio Iowa, Axios Des Moines, KCRG/WHO13/WOI, Ballotpedia, BallotReady.
3. Candidates' own campaign websites. Use these for each candidate's stated positions and label them as self-reported.
4. Voting records: legis.iowa.gov for state legislators, congress.gov for Nunn and Hinson.
5. Partisan or advocacy sources (see Section 6). Use only to document what a side argues, and label them that way.

**Currency.** Use only sources about the November 2026 general election, or background facts that don't change. Discard primary-season pages about candidates who are no longer on the ballot.

**Per-race output template**
```
## <Race>
What the office does (1–2 sentences, official source)
| | Candidate A | Candidate B | (C) |
|---|---|---|---|
| Party / incumbent? | | | |
| Current/prior roles | | | |
| Education | | | |
| Top 3 stated priorities (self-reported) | | | |
| Record/votes relevant to the office | | | |
| Key differences on issues voters asked about | | | |
| Endorsements (major, factual) | | | |
| Sources | | | |
Open questions / couldn't verify:
```

**Known fetching issue.** Some sites (iowacapitaldispatch.com, polkcountyiowa.gov) blocked plain fetches. A scraper with bot handling, such as Firecrawl, worked.

---

## 2. Ballot (from the official sample ballot)

Source: https://www.polkcountyiowa.gov/media/2pmjyqt4/clive_4-sample.pdf (Clive 4, precinct 11100)

**Partisan races**

| Race | Candidates |
|---|---|
| U.S. Senate | Ashley Hinson (REP), Josh Turek (DEM), Thomas Laehn (LIB) |
| U.S. House, District 3 | Zach Nunn (REP), Sarah Trone Garriott (DEM) |
| Governor / Lt. Governor | Zach Lahn / Derek Wulf (REP); Rob Sand / Dave Muhlbauer (DEM) |
| Secretary of State | Paul D. Pate (REP), Ryan Peterman (DEM) |
| Auditor of State | Chris Cournoyer (REP), Taylor Wettach (DEM) |
| Treasurer of State | Roby Smith (REP), John Norwood (DEM) |
| Secretary of Agriculture | Mike Naig (REP), Chris Jones (DEM) |
| Attorney General | Brenna Bird (REP), Nate Willems (DEM) |
| State Representative, District 32 | Mike Jones (DEM), unopposed |
| County Supervisor, District 1 | John Forbes (DEM), unopposed |
| County Treasurer | Mary L. Wells (DEM), unopposed |
| County Recorder | Lisa J. Chiodo (DEM), unopposed |
| County Attorney | Jonah Dyer (REP), Kimberly Graham (DEM) |

**Nonpartisan races**

| Race | Candidates |
|---|---|
| County Hospital Trustee (vote for 2) | Emily Webb, Emily Westergaard, Abu Bakarr Sillah |
| Soil & Water Commissioner (vote for 2) | Deborah Neustadt, Douglas R. Zehr, Kirk Norris, Autumn L. Ogden |
| Agricultural Extension Council (vote for 5) | Angela Hilbert, Cynthia Twedt, Emma Runde, Dennis H. Goering, Jennifer Quiner |
| Agricultural Extension Council, to fill vacancy (vote for 1) | Harrison Furlow |

**Judicial retention (yes/no on each judge)**
- Court of Appeals: Sharon Soorholtz Greer, John M. Sandy, Julie A. Schumacher
- District 5C Judges: Scott J. Beattie, Sarah Crane, Celene Gogerty, Samantha J. Gronewald, Christopher Kemp, Coleman McAllister, Lawrence P. McLellan, Joseph W. Seidlin
- District 5C Associate Judges: Kimberly Ayotte, Brendan L. Greiner, Lynn Poschner, Tabitha Turner, Jordan Brackey, Ashley Stewart

**Constitutional Amendment 1:** Would require a two-thirds vote of both legislative chambers to raise individual or corporate income tax rates, or to create a new income tax.

---

## 3. Summary so far (from the chat)

These are short summaries. Each line should be verified and expanded in the fan-out.

**Abbreviations used below:**
- ICD = Iowa Capital Dispatch voter guide
- TD = The Times-Delphic (Drake student paper) ballot guide, published Nov 2, 2026
- DMR = Des Moines Register

### U.S. Senate (open seat; Joni Ernst retiring)
- **Hinson (R), 41.** U.S. Rep. since 2021, former state representative, former KCRG anchor. She has pledged to be Trump's "strongest ally." Stated priorities: border security and deportations, keeping transgender women out of women's sports, farmers, and "strengthening" Medicaid, Medicare and Social Security. Also supports year-round E15 and school choice (TD). (ICD)
- **Turek (D), 47.** State representative for House District 20 (Council Bluffs) since 2023; Paralympic gold medalist. Proposes a ban on food price gouging, a ban on private equity buying homes and farmland, a higher minimum wage, restoring Medicaid and SNAP funding cut in 2025, a public health insurance option, a ban on corporate PAC money, overturning Citizens United, and term limits for Congress and the Supreme Court. (ICD)
- **Laehn (L), 44.** Two-term Greene County Attorney and the first Libertarian elected to partisan office in Iowa; former political science professor. Priorities: ending federal tax credits for carbon pipelines and eminent domain "abuse," requiring congressional approval for war, limiting PACs and super PACs, reducing the national debt, and leaving abortion law to the states. (ICD, TD)

### U.S. House, District 3
- **Nunn (R, incumbent), 45.** In Congress since 2023; former state senator and representative; Air Force Reserve colonel. Emphasizes bipartisanship, defense and veterans issues, and support for the 2025 tax law. TD adds: lower spending, abortion restrictions, ethanol. (ICD, TD)
- **Trone Garriott (D), 48.** State senator since 2020; Lutheran pastor in Clive. Would reverse the 2025 Medicaid cuts and restore the lapsed ACA subsidies. TD adds: Medicare and Social Security, public schools, clean energy, immigration pathways. (ICD, TD)

### Governor / Lt. Governor (open seat)
- **Lahn (R), 40, with Wulf.** Belle Plaine farmer and entrepreneur; formerly with Americans for Prosperity. Wulf is a first-term state representative and farmer. Priorities: rural communities, anti-abortion measures, "Make Iowa Healthy Again," farm consolidation and out-of-state land ownership, cancer rates, schools, lower taxes, and ending state benefits for people in the country illegally. (ICD, TD)
- **Sand (D), 44, with Muhlbauer.** State Auditor since 2019; former assistant attorney general who prosecuted the Hot Lotto fraud case. Muhlbauer is a Crawford County supervisor and farmer. Proposals: age and term limits for officials, mandatory prison sentences for stealing more than $10,000 in public money, audits and term limits for the Education Savings Account program, legal and regulated cannabis, a social media ban for children under 16, ending Medicaid privatization, and a higher minimum wage. (ICD, TD)

### Secretary of State
- **Pate (R, incumbent), 68.** In office since 2015 (also 1995–99); former Cedar Rapids mayor and state senator. Points to voter ID, election security, and checking voters' citizenship through the federal SAVE database. (ICD)
- **Peterman (D), 35.** Former Navy helicopter pilot; Naval Academy graduate; former U.S. Senate fellow. Opposes sharing voter data with the U.S. Justice Department, the shortened early-voting window, and the ban on non-English ballots. (ICD)

### Auditor of State (open seat)
- **Cournoyer (R), 55.** Current lieutenant governor; former state senator and tech consultant. Priorities: government efficiency, the governor's DOGE task force recommendations, and AI tools in auditing. (ICD, TD)
- **Wettach (D), 35.** Muscatine lawyer who left Simpson Thacher after the firm's deal with the Trump administration. Would continue the office's efficiency (PIE) program, protect its independence, and seek repeal of the 2023 law limiting the auditor's access to information. (ICD)

### Treasurer of State
- **Smith (R, incumbent), 49.** Treasurer since 2023; state senator 2011–22; former banker. Priorities: financial literacy and promoting the 529 and IABLE savings programs. (ICD)
- **Norwood (D), 62.** Goldman Sachs 10,000 Small Businesses advisor; former soil and water commissioner; ran for Secretary of Agriculture in 2022. Would invest state funds through local banks and credit unions and have the IPERS board, not the governor, choose its CEO. (ICD)

### Secretary of Agriculture
- **Naig (R, incumbent), 48.** In office since 2018. Priorities: the agriculture industry, animal health, food safety, water quality and soil health. Points to the 2026 "Farm to Faucet" law. (ICD)
- **Jones (D), 65.** Water quality scientist with a PhD. Proposes crop diversification, taxpayer-funded transition help ("off ramps") for farmers, and regulation of nutrient inputs. (ICD)

### Attorney General
- **Bird (R, incumbent), 50.** In office since 2023; former Guthrie County Attorney. Points to support for crime victims and police, lawsuits against tech companies (Roblox, OpenAI), a cold case unit, and an antisemitism task force. (ICD, TD)
- **Willems (D), 47.** Cedar Rapids labor and workers' compensation lawyer; state representative 2008–12. Proposes a wage-theft recovery unit, tougher penalties for polluters, and stronger consumer protection. (ICD)

### County Attorney
- **Dyer (R), 43.** Johnston resident; defense lawyer since 2010; founder of JHD Law. Nominated at a special GOP convention on June 27. Says his priorities are protecting victims, holding offenders accountable, and enforcing the law fairly. (DMR via Yahoo, Axios, TD)
- **Graham (D, incumbent).** County Attorney since 2023; previously a juvenile court attorney and guardian ad litem for more than 20 years. Elected in 2022 on a reform platform. Plans to expand the Special Victims Bureau, hire an in-house social worker, and offer a free child internet safety class. (TD, prior DMR and WOI coverage)

### Unopposed races
- **State Rep. HD32: Mike Jones (D).** BallotReady lists him as the current Windsor Heights mayor. Not yet verified further.
- **Supervisor D1: John Forbes (D).** Former state representative (District 40); beat incumbent Matt McCoy in the June primary; lost the District 2 supervisor race in 2024.
- **Treasurer: Mary L. Wells (D).** Treasurer since 2021; focused on wait times and online services. (TD)
- **Recorder: Lisa J. Chiodo (D).** Nine years in the recorder's office; focused on service and property-fraud prevention. (TD)

### Nonpartisan races (TD)
- **Hospital Trustee (Broadlawns):** Webb (current board chair, technology attorney); Westergaard (board member, former Broadlawns Foundation chair); Sillah (Census Bureau field supervisor; priorities: access, quality of care, finances, community input).
- **Soil & Water Commissioner:** Neustadt (retired educator, clean-water advocate); Zehr (retired professor, PhD); Norris (president and CEO of the Iowa Hospital Association); Ogden (farmer, incumbent commissioner, youth outreach).
- **Extension Council:** No information found for Hilbert, Twedt, Runde, Goering, or Quiner. Furlow (vacancy seat) is public policy director for the Iowa Pork Producers Association.

### Judges
- The ISBA 2026 Judicial Performance Review was published Oct 7, 2026. 964 attorneys responded. Judges are scored 1–5 on 10–12 traits, plus a percentage of lawyers saying "retain."
- Court of Appeals "retain" percentages (The Gazette):
  - Schumacher: 92.7% (appointed 2019)
  - Soorholtz Greer: 90.9% (appointed 2019)
  - Sandy: 87.8% (appointed 2024)
- District 5C numbers were not found yet. Pull them from the ISBA review.

### Amendment 1
- **Supporters** (e.g., Iowans for Tax Relief) say it gives tax certainty and requires broad agreement before income taxes rise.
- **Opponents** (e.g., Common Good Iowa) say it gives a legislative minority outsized power and could shift the tax burden to sales taxes and fees, which still need only a simple majority.
- **History:** The legislature passed the amendment in 2024 and again in 2026. A similar 1999 amendment failed 52–48.
- **Polling:** An August 2026 Suffolk poll found voters closely split. Shown here for context only; leave it out of the final comparison.

---

## 4. Fan-out task list (one subtask each)

1. U.S. Senate (3 candidates). Add: congress.gov votes for Hinson; legis.iowa.gov votes for Turek (e.g., his 2024 vote on the amendment language); stated positions on cost of living, health care, farm bill, immigration, and abortion from campaign sites.
2. U.S. House District 3. Add: Nunn's key House votes; Trone Garriott's Iowa Senate record.
3. Governor / Lt. Governor. Add: positions on property taxes, the Education Savings Account program, water quality and cancer, abortion, Medicaid. Add bios for Wulf and Muhlbauer.
4. Secretary of State. Add: what the office controls; the voter-data sharing issue (facts from both sides).
5. Auditor. Add: details of the 2023 audit-access law; the DOGE task force.
6. Treasurer. Add: IPERS governance; what the office manages.
7. Secretary of Agriculture. Add: the Farm to Faucet law; the Oct 2, 2026 debate coverage (ICD).
8. Attorney General. Add: Bird's multistate and tech lawsuits; Willems' platform details.
9. County Attorney. Add: Graham's record in office (programs, policies); Dyer's full DMR questionnaire answers.
10. Unopposed races (HD32, Supervisor D1, Treasurer, Recorder). Short bios only.
11. Hospital Trustee. Add: Broadlawns board role; incumbents' records.
12. Soil & Water. Bios.
13. Extension Council. Find any information on the 5 candidates (ISU Extension Polk, local news, Ballotpedia).
14. Judges. Extract each District 5C judge's percentages and scores from the ISBA review, plus appointment year and bio from iowacourts.gov.
15. Amendment 1. Full text, the legislative votes in both years, and equal-length pro and con arguments.

---

## 5. Sources

### Official
- Sample ballot (Clive 4): https://www.polkcountyiowa.gov/media/2pmjyqt4/clive_4-sample.pdf
- Polk County candidate list (includes candidate emails): https://www.polkcountyiowa.gov/media/4xehjvif/candidate-list.pdf
- Kimberly Graham county page: https://www.polkcountyiowa.gov/county-attorney/kimberly-graham/
- Iowa voter info: https://voterready.iowa.gov/
- Amendment 1 text (SJR 11, 91st General Assembly): https://www.legis.iowa.gov/docs/publications/LGE/91/SJR11.pdf
- Iowa Judicial Branch retention news release: https://www.iowacourts.gov/newsroom/news-releases/information-about-iowas-2026-judicial-retention-elections
- Judge bios (pattern): https://www.iowacourts.gov/iowa-courts/district-court/judicial-district-5/judges-and-magistrates/<name>
- ISBA Judicial Performance Review: https://www.iowabar.org/?pg=JudicialEvaluations
- ISBA blog post on 2026 results: https://www.iowabar.org/?pg=IowaBarBlog&blAction=showEntry&blogEntry=152694

### Iowa Capital Dispatch voter guide (main source)
- Index: https://iowacapitaldispatch.com/voter-guides/2026-iowa-general-election/
- U.S. Senate: https://iowacapitaldispatch.com/voter-guides/contests/2026-u-s-senate-general/
- U.S. House District 3: https://iowacapitaldispatch.com/voter-guides/contests/2026-us-house-district-3-general/
- Governor: https://iowacapitaldispatch.com/voter-guides/contests/2026-iowa-governor-general/
- Secretary of State: https://iowacapitaldispatch.com/voter-guides/contests/2026-iowa-secretary-of-state/
- Auditor: https://iowacapitaldispatch.com/voter-guides/contests/2026-iowa-auditor-general/
- Treasurer: https://iowacapitaldispatch.com/voter-guides/contests/2026-iowa-treasurer/
- Secretary of Agriculture: https://iowacapitaldispatch.com/voter-guides/contests/2026-iowa-secretary-of-agriculture/
- Attorney General: https://iowacapitaldispatch.com/voter-guides/contests/2026-iowa-attorney-general/
- Amendment 1: https://iowacapitaldispatch.com/voter-guides/ballot-measures/amendment-1-tax-increases/

### Other news and guides
- The Times-Delphic ballot guide (Nov 2, 2026): https://timesdelphic.com/85586/news/a-guide-to-the-2026-midterms-ballot/
  - Note: it covers Des Moines precinct 32, which overlaps but is not identical to Clive 4.
  - It wrongly says Hinson is "running for re-election." She is running for an open Senate seat.
- KCRG Senate overview (Nov 2): https://www.kcrg.com/2026/11/02/election-results-nation-watches-iowa-votes-fill-us-senate-seat/
- CBS2 Iowa midterm overview: https://cbs2iowa.com/news/local/beyond-the-podium-2026-iowa-midterm-election
- WOI Senate overview: https://www.weareiowa.com/article/news/politics/elections/iowa-senate-election-results-ashley-hinson-josh-turek-thomas-laehn-winner-updates/524-5b0a59b6-e43b-4797-8d93-4b400c086686
  - Note: it says Turek serves in the "State Senate," but ICD and other sources say he serves in the Iowa House. Verify.
- Ballotpedia, U.S. Senate in Iowa 2026: https://ballotpedia.org/United_States_Senate_election_in_Iowa,_2026
- Ballotpedia News on the Senate race: https://news.ballotpedia.org/2026/08/06/turek-hinson-running-for-open-u-s-senate-seat-in-iowa-as-ernst-retires/
- DMR (via Yahoo), County Attorney candidates: https://www.yahoo.com/news/politics/articles/running-polk-county-attorney-meet-130051252.html
- Axios Des Moines, GOP enters county races: https://www.axios.com/local/des-moines/2026/06/30/scoop-republicans-enter-polk-county-races-for-supervisor-and-attorney
- BallotReady, Kimberly Graham: https://www.ballotready.org/people/kimberly-graham-53a8680e-880c-49f0-a966-971649adc036
- BallotReady, Mike Jones: https://www.ballotready.org/people/mike-jones-04cf679d-e458-4b56-89ed-bbce6015f209
- The Gazette on judges: https://www.thegazette.com/news/crime-and-courts/flip-over-ballot-to-view-iowa-judges-up-for-retention/article_79c91e56-be0c-4e29-8fb4-02e58c4c9a17.html
- Radio Iowa on the ISBA review: https://www.radioiowa.com/2026/10/13/state-bar-association-reviews-iowa-judges-up-for-retention/
- The Gazette on the Amendment 1 opposition campaign: https://www.thegazette.com/news/elections/iowa-coalition-launches-campaign-against-income-tax-amendment/article_2295365b-9049-4b10-8b82-4aaea26d31ec.html
- Iowa Public Radio Amendment 1 explainer: https://www.iowapublicradio.org/political-news/2026-10-13/iowa-constitutional-amendment-1-tax-increases-2026-election
- KIWA Radio Amendment 1 guide: https://kiwaradio.com/news/what-would-iowas-amendment-1-change-a-guide-to-the-income-tax-ballot-question/
- WHO13, Supervisor primary: https://who13.com/news/two-democrats-face-off-for-polk-county-supervisor-in-district-4/amp/

### Candidate campaign sites (self-reported positions)

| Candidate | Site |
|---|---|
| Hinson | https://ashleyhinson.com/ |
| Turek | https://turek4iowa.com/platform/ |
| Laehn | https://laehn4iowa.org/issues |
| Nunn | https://zachnunn.com/ |
| Trone Garriott | https://sarahforiowa.com/ |
| Lahn | https://www.zachlahn.com/ |
| Sand | https://robsand.com/ |
| Pate | https://pateforiowa.com/ |
| Peterman | https://petermanforiowa.com/ |
| Cournoyer | https://cournoyerforiowa.com/ |
| Wettach | https://wettachforiowa.com/ |
| Smith | https://robysmith.com/ |
| Norwood | https://www.norwood4iowa.com/ |
| Naig | https://www.mikenaig.com/ |
| C. Jones | https://chrisjonesforiowa.com/ |
| Bird | https://birdforiowa.com/ |
| Willems | https://www.natewillems.com/ |
| Dyer | https://jonahforpolkcountyattorney.com/ |
| Chiodo | https://votechiodo.com/ |
| Sillah | https://abusillahcampaignwebsite.com/ |
| Ogden | https://www.griffieonfamilyfarm.com/meet-the-candidate.html |
| Webb | https://www.broadlawns.org/about/board-of-trustees/emily-webb |
| Westergaard | https://www.broadlawns.org/about/board-of-trustees/emily-westergaard |

---

## 6. Partisan or advocacy sources seen

Use these only to document what a side argues, and label them that way.

- Bleeding Heartland (progressive blog). Its judge-ratings roundup is a useful pointer to ISBA data: https://www.bleedingheartland.com/2026/10/13/highest-and-lowest-rated-judges-on-iowas-2026-ballot/
- Scott County Democrats, "Vote NO" on Amendment 1
- Townhall (conservative), on Turek and Amendment 1
- National Review (conservative), pro-Amendment 1 op-ed
- bluevoterguide.org (progressive endorsements); ivoterguide.com (conservative)
- Letters to the editor and Substack endorsements

---

## 7. Gaps to close
- District 5C judges' ISBA percentages and scores.
- Extension Council candidates (5 of the 6 have no information yet).
- Mike Jones (HD32) bio and platform.
- John Forbes' 2026 platform for District 1.
- Running-mate bios (Wulf, Muhlbauer).
- Voting records for incumbents and legislators.
- Resolve the Turek "State Senate" vs. "Iowa House" inconsistency (most sources say House District 20).
