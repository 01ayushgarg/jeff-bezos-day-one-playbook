# Worked example: a Day 1 review of *Fernhill*

> **Fictional.** Fernhill, its people and every number below are invented to show how the skill works.
> Nothing here is a claim about any real company. Quotes from Jeff Bezos are real and cited.

## What the founder sent

```text
Run a Jeff Bezos-style Day 1 review on my company.

What we do: Fernhill makes scheduling and records software for independent veterinary clinics.
Customer: the clinic's front-desk staff and vets. The clinic owner signs the contract.
Size: 85 people, 1,400 clinics, growing 35% a year, 22 months of cash.
Last quarter we shipped: 9 features. Most were matching a competitor's release.
Weekly metrics: new clinics signed, support tickets closed per agent, NPS, uptime.
Open decisions: 14, some waiting over a month. Pricing changes go to the exec meeting.
Bets running: an AI note-taker for vets, a pet-owner app, a move into large hospital chains.
What makes us different: honestly, not sure any more.
Something else: our CTO wants to leave and start her own company and asked me what I think.
```

## What the skill returned

### Day 2 audit

| Defense | Score | Evidence |
|---|---|---|
| Customer obsession | Red | 6 of 9 features started from a competitor's release notes |
| Skeptical view of proxies | Red | *Tickets closed per agent* rises while clinics complain that problems come back |
| External trends | Green | The AI note-taker uses the biggest trend in the field |
| High-velocity decisions | Red | Pricing changes (two-way doors) take a median of 24 days |

"customers are always beautifully, wonderfully dissatisfied, even when they report being happy and business is
great." [L2016] Fernhill's NPS of 51 says little about what clinics want next. **Our reading:** fix decision
velocity first; it's the cheapest, and it unblocks the others.

### Customers and what won't change

- **The customer:** the front-desk lead and the vets, not the owner who signs [ECW18].
- **Stable needs (ten years):** appointments that don't get lost; records a vet can find in seconds; fewer
  minutes of admin per appointment; reliable uptime. "think about the things that are not going to change over
  10 years. And those are probably the big things." [LEX405 01:36:55]
- **Share of effort on stable needs:** about 30%. Most work went to matching features.
- **Roadmap:** the pet-owner app was *asked for* by nobody; it's an invention on the clinic's behalf, but no one
  has tested it [L2018]. The note-taker came from vets complaining about evening paperwork: *asked for*, in
  effect.

### Inputs and cash

- **Output:** cash burn per clinic served, moving toward free cash flow per share (our suggestion for their
  stage).
- **Inputs they'll manage:** minutes of admin per appointment, record-search time, repeat tickets per clinic,
  uptime. Their old goals list had 18 goals; 11 mentioned revenue or signings.
- **Cash test:** the hospital-chain move needs an enterprise sales team and a compliance program. Year one
  earnings impact looks positive on paper; cumulative free cash flow is -$4.2M by year two. "Paradoxically,
  from a cash flow perspective, the slower this business grows the better off it is." [L2004] That was his
  invented machine business, not a rule; here it means they model a slower version (two pilot chains first).

### Proxy audit

*Tickets closed per agent* was chosen four years ago to measure support quality. It is now a proxy for speed,
not for problems solved. "that metric is not actually customer happiness. It's a proxy for customer
happiness." [LEX405 01:26:04] The anecdote check: the founder calls three clinics that had tickets closed last
week; two say the problem came back. They add *repeat tickets within 30 days* and stop ranking agents on closes.

### Decisions

| Decision | Door | Decider | Decide by | Check on |
|---|---|---|---|---|
| Price change for multi-vet clinics | Two-way | Head of revenue | Friday | 60 days |
| Pet-owner app: continue or pause | Two-way | Product lead | This week | After test |
| Hospital chains: full move | One-way (team, contracts, compliance) | CEO and board | After pilots | n/a |
| Rewrite the records database | One-way (data migration) | CTO and CEO, slowed down | After three more analyses | n/a |
| 10 other items | Two-way | Named owners | 5 days each | 30 to 60 days |

"Type 2 decisions can and should be made quickly by high judgment individuals or small groups." [L2015] The
CTO and head of product disagree on pausing the pet-owner app; it's a judgment call with no clear data. The CTO
says she disagrees and commits [L2016], and a two-week test runs.

### Bets

| Bet | Odds (honest) | Payoff if it works | Stop signal | Double-down signal |
|---|---|---|---|---|
| AI note-taker | 40% | Saves vets ~45 min a day; strong retention driver | Under 30% weekly use after 60 days | Over 60% weekly use |
| Pet-owner app | 10% | Could become a second customer side for the loop | Under 5% of a clinic's clients sign up in 8 weeks | Over 20% |
| Hospital chains | 25% | 3x revenue in five years | Pilots need more than 6 months of custom work | Both pilots live in 4 months |

- **Failure budget:** 15% of engineering time this year (our suggestion), written down so a stopped bet isn't
  treated as a disaster.
- "If the size of your failures isn't growing, you're not going to be inventing at a size that can actually
  move the needle." [L2018] **Our reading:** at 85 people, *growing* means one bet a year big enough to hurt
  if it fails, not a multibillion-dollar one.

### Standards

- **Domain:** product specs. Specs today are slide decks written in an afternoon.
- **What good looks like:** two past specs everyone agrees were excellent, both written as prose.
- **Realistic scope:** a week for any spec that changes a clinic's daily workflow. "Unrealistic beliefs on scope
  – often hidden and undiscussed – kill high standards." [L2017] They switch the monthly roadmap review to
  six-page memos read in the room (chapter 11).

### What makes us different

The distinctiveness check produces a line the team agrees on: *the fastest front desk in veterinary care*.
Three of the six competitor-matching features don't fit it and are frozen. "The world wants you to be typical –
in a thousand ways, it pulls at you. Don't let it happen." [L2020]

### The CTO's question

This is a personal one-way door for the CTO, not a company decision, so the skill offered her the
regret-minimization exercise rather than advice from the founder (`templates/08-regret-minimization.md`). The
founder's part: be honest about Fernhill's odds and hers. "Most regrets, by the way, are acts of omission and
not commission." [AOA01] She decides to stay through the database decision and leave in nine months, with a
handover plan.

### This quarter

1. Push two-way doors down: named owners, five-day deadlines, a check date on each. Owner: CEO.
   [L2016, LEX405 01:01:29]
2. Replace *tickets closed* with *repeat tickets within 30 days*; run an anecdote check every week. Owner: head
   of support. [LEX405 01:34:00]
3. Write the stop and double-down signals for all three bets and start the two hospital pilots. Owner:
   product lead. [L2015]

### Where to be careful

- Amazon's examples come from a company thousands of times larger. Every threshold here (15%, five days, a
  week for a spec) is our suggestion, sized for 85 people.
- The proxy and anecdote material comes from a 2023 interview, not a letter.
- The CTO's decision is hers; the framework is a way to think, not a verdict.

## The result (invented)

Median time on two-way doors fell from 24 days to 4. Repeat tickets fell by a third in two months. The
pet-owner app hit its stop signal and was paused; two of its engineers moved to the note-taker, which reached
58% weekly use. Both hospital pilots went live in five months, slower than the double-down signal, so the full
move waits another quarter.
