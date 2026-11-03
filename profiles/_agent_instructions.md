# Instructions for per-race profile agents

Context: Polk County, Iowa (Clive 4 precinct) general election, Tuesday Nov 3, 2026. Today is Nov 2, 2026.
Read `/Users/matthewpick/repos/iowa-election-2026/clive4_ballot_research_brief.md` first. Its Section 1 has the neutrality rules and source order, Section 3 has a summary to verify and build on, and Section 5 lists starting sources for your race.

## Goal
Write an in-depth, neutral profile of **each candidate** in your race. Each profile should be **at most 2 printed pages (about 700–1,000 words)**. Then write a side-by-side comparison of the candidates. Every candidate gets the same structure, depth, and kinds of sources.

## Tools
- Use Firecrawl for search and scraping: `mcp__claude_ai_Firecrawl__firecrawl_search` / `mcp__claude_ai_Firecrawl__firecrawl_scrape`. If those are unavailable, use `mcp__firecrawl__firecrawl_search` / `mcp__firecrawl__firecrawl_scrape`. Some sites block plain fetches (iowacapitaldispatch.com, polkcountyiowa.gov); Firecrawl handles them.
- Fetch the candidates' campaign sites, the Iowa Capital Dispatch voter-guide page for the race, Ballotpedia, and official records (legis.iowa.gov, congress.gov, the state agency's site). Add Des Moines Register, Radio Iowa, IPR, The Gazette, Axios Des Moines, and KCRG/WHO13/WOI coverage of the general election (debates, forums, questionnaires).
- Be efficient. Aim for about 15–30 fetches in total. Don't fetch the same page twice.

## Neutrality rules (strict)
- Report facts, records, votes, and each candidate's own stated positions. Label campaign-site claims as self-reported ("Hinson's campaign says…").
- No recommendations, endorsements, predictions, polls, or horse-race analysis.
- Attribute every criticism to whoever made it. Include the other side's response where one exists.
- Give every candidate the same depth. If one candidate has less public record, say so plainly. Don't pad the other profiles to match.
- Every factual claim needs a source. Cite inline with bracketed numbers, e.g. [3], that map to the Sources list at the end of the file.
- If you can't verify something, put it under "Open questions / couldn't verify." Don't guess.

## Output file format (Markdown)
Write exactly one file to the path given in your task.

```
# <Race> — Candidate Profiles
_What the office does_ (2–3 sentences, official source cited)
_Ballot order / candidates_; one-line note on whether it's an open seat or has an incumbent

## <Candidate A> (<Party>)  [repeat for each candidate, same headings]
### At a glance
- Age / hometown / current role / education / career bullets
### Background & career
### Track record
(Votes, bills sponsored, actions in office, cases, audits, and so on, specific and with dates. For non-officeholders: professional record.)
### What they're running on
(Top priorities and specific proposals, self-reported, with notes from debates or forums)
### Positions on key issues
(Short bullets on the issues relevant to this office)
### Endorsements & funding
(Major, factual; fundraising totals from official or news sources if available)
### Criticisms & responses
(Attributed criticism, each paired with the candidate's response)

## Head-to-head comparison
Comparison table across issues, followed by a short neutral prose section, "Where they differ most," with no judgments.

## Open questions / couldn't verify

## Sources
Numbered list: [n] Title — Publisher — URL (accessed Nov 2, 2026). Label campaign sites "(campaign, self-reported)" and advocacy sources "(advocacy)".
```

When you finish, reply with only: the file path, the word count per candidate profile, and a list of any major gaps. Don't include the profile content in your reply.
