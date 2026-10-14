---
name: jeff-bezos-day-one-playbook
description: Run a Jeff Bezos-style Day 1 review on a company, team, product or decision (the Day 2 audit, customer obsession and working backwards, what won't change in ten years, inputs over outputs and free cash flow, one-way and two-way doors, high standards, experiments and big bets, resisting proxies, the hiring bar, the flywheel, six-page memos, differentiation, and regret minimization for personal decisions), using only his own words in his 1997 to 2020 letters to Amazon shareholders, the 2001 Academy of Achievement interview, the 2018 Economic Club of Washington interview and the 2023 Lex Fridman interview, with every point cited. Use when someone says their company is getting slow or bureaucratic, needs to decide faster, is stuck in a disagreement, wants to start a product from the customer, is choosing metrics or goals, is planning experiments or a big bet, wants to raise the quality bar, is hiring a key role, is replacing slide decks with memos, is mapping their business model's loop, is facing a career or life decision, or asks 'what would Jeff Bezos do'. Triggers on 'Day 1', 'Day 2', 'it's still Day 1', 'customer obsession', 'customer-obsessed', 'working backwards', 'work backwards from the customer', 'one-way door', 'two-way door', 'Type 1 decision', 'Type 2 decision', 'disagree and commit', '70% of the information', 'high-velocity decisions', 'high standards', 'six-page memo', 'narrative memo', 'no PowerPoint', 'study hall', 'resist proxies', 'process as proxy', 'data vs anecdotes', 'input metrics', 'free cash flow per share', 'long-term thinking', 'what won't change in 10 years', 'flywheel', 'bold bets', 'failure and invention', 'wandering', 'missionaries vs mercenaries', 'raise the bar', 'regret minimization', 'create more than you consume', 'be distinctive', 'what would Bezos do'.
---

# Jeff Bezos' Day 1 Playbook

An unofficial, sourced method for reviewing a company, a team or a decision the way Jeff Bezos describes
running Amazon in his letters to shareholders (1997 to 2020) and three long interviews. Who he is, for this
playbook: `references/00-who-is-jeff-bezos.md`.

> "Day 2 is stasis. Followed by irrelevance. Followed by excruciating, painful decline. Followed by death. And
> that is why it is always Day 1." [L2016]

## Ground rules for the agent

- Every point cites a source ID (e.g. `[L1997]`, `[L2016]`, `[LEX405 01:00:06]`, `[AOA01]`, `[ECW18]`, see
  `SOURCES.md`). **Never put words in his mouth.** If the playbook doesn't cover something, say so.
- **Only his words are his.** The letters include quotes from customers, sellers, authors, a handstand coach,
  Benjamin Graham, Richard Dawkins and Amazon's Leadership Principles: none of those is Bezos. In the
  interviews, only his answers are his; Lex Fridman, David Rubenstein and the Academy's editors are not him.
  The Economic Club transcript's explanatory footnotes are the Club's.
- **The 2021 and later letters are Andy Jassy's** and are not used.
- **Not in these sources, so not his method here:** the press release and FAQ format, the *bar raiser* role,
  *two-pizza teams*, *your margin is my opportunity*, and *good intentions don't work, mechanisms do*. You can
  mention that these are attributed to him elsewhere, but don't cite or quote them.
- Quote briefly and exactly. Steps, thresholds, templates and applications to the user's situation are labelled
  as our reading or our suggestion.
- **Date everything.** Say *in 1997* or *in the 2016 letter*. Where his view changed (Day 1, growth versus cash
  flow, hiring versus standards, physical stores), show both dates.
- **Scale matters.** His examples are from one of the largest companies in the world. Translate the test, not
  the example. *Multibillion-dollar failures* are for Amazon, not for a ten-person start-up.
- **Not covered:** his politics, private life, wealth, philanthropy, and disputes about Amazon (including labor
  relations). Decline to use this skill for those.
- **His own caveat:** "We never claim that our approach is the right one – just that it's ours" [L2015]. If the
  honest conclusion is that his approach doesn't fit the user's situation, say so.

---

## Step 1: Get the facts (ask only what you can't see)

1. What do you do, for which customer, in one sentence? Who pays or decides but isn't the customer? [ECW18]
2. What did you ship in the last quarter, and where did each idea come from? [L2016]
3. What metrics does leadership review every week, and why each one? [LEX405 01:24:36]
4. The open decisions, and roughly how long each has been waiting. [L2016]
5. The bets and experiments running now, and what each costs. [L2015]
6. What makes you different, in one line? [L2020]
7. Size, stage, and cash position (how long the money lasts). [L2004]

For a personal decision, skip to Step 6.

## Step 2: Pick the chapters that fit

| If the problem is... | Run | Chapter |
|---|---|---|
| Slow, bureaucratic, *we used to be faster* | Day 2 audit | `01-day-1-vs-day-2.md` |
| Roadmap driven by competitors or by existing skills | Working-backwards brief | `02-customer-obsession-and-working-backwards.md` |
| No long-term priorities; chasing quick wins | Stable-needs map | `03-what-wont-change-and-long-term-thinking.md` |
| Goals are all revenue and profit; growth burns cash | Input tree and cash test | `04-cash-flow-inputs-and-outputs.md` |
| Decisions stuck, arguments by stamina | Door log | `05-one-way-and-two-way-doors.md` |
| Quality uneven; work takes *too long* | Standards check | `06-high-standards.md` |
| No experiments, or bets with no stop signals | Experiment portfolio | `07-invention-failure-and-big-bets.md` |
| Metrics look fine but customers complain | Proxy audit | `08-resist-proxies-and-tell-the-truth.md` |
| Hiring a key role | Hiring bar | `09-hiring-and-the-bar.md` |
| Unclear business model economics | Loop map | `10-the-flywheel-and-scale-economics.md` |
| Slide decks, meetings without decisions | Six-page memo | `11-memos-not-slides.md` |
| A personal or career one-way door | Regret minimization | `12-regret-minimization.md` |
| Becoming *me too*; unclear value to stakeholders | Value ledger, distinctiveness check | `13-differentiation-and-creating-more-than-you-consume.md` |

## Step 3: The Day 2 audit (always run this for a company or team)

Score the four defenses from the 2016 letter green, amber or red: customer obsession, a skeptical view of
proxies, eager adoption of external trends, high-velocity decision making [L2016]. Use the evidence from Step 1.
**Our suggestion:** fix one red per quarter. → `templates/01-day-2-audit.md`

## Step 4: Customers, what won't change, and inputs

- Name the customer. Mark each roadmap item as *asked for* or *invented on their behalf* [L2009, L2018].
- List the needs that won't change in ten years [L2008, LEX405 01:36:55] and check where effort goes.
- Rewrite output goals as controllable inputs [L2009]. Run the cash test on any capital-hungry growth plan
  [L2004].
→ `templates/02-working-backwards-brief.md`, `templates/07-proxy-and-input-audit.md`

## Step 5: Decisions, bets and standards

- Sort open decisions into one-way and two-way doors. Two-way doors go to one owner with a deadline in days, at
  about 70% of the information [L2015, L2016, LEX405 01:01:29]. One-way doors go up and slow down
  [LEX405 01:00:06]. Disagree and commit, or escalate real misalignment [L2016].
- List bets with odds, payoff, a stop signal and a double-down signal; set a failure budget sized to the
  company [L2015, L2018].
- Pick the one domain where quality matters most and run the standards check: recognize, scope, skill, teach
  [L2017].
→ `templates/03-door-decision-log.md`, `templates/05-experiment-and-failure-budget.md`,
`templates/04-high-standards-checklist.md`

## Step 6: People and personal decisions

- Hiring: the three 1998 questions and the missionary test [L1998, ECW18]. → `templates/06-hiring-bar.md`
- A personal one-way door: the regret-minimization exercise [AOA01, ECW18]. → `templates/08-regret-minimization.md`

## Step 7: Deliver the Day 1 review notes

```markdown
# Day 1 review: [company / team / decision]

**Customer:** [one line] · **What makes us different:** [one line] · **Date:** [yyyy-mm-dd]

## Day 2 audit
| Defense | Score | Evidence |
|---|---|---|
| Customer obsession | | |
| Skeptical view of proxies | | |
| External trends | | |
| High-velocity decisions | | |

## Customers and what won't change
- Stable needs (ten years): ___ · Share of effort on them: ___%
- Roadmap: ___ asked for · ___ invented on their behalf

## Inputs and cash
- Output we care about: ___ · Inputs we'll manage: ___
- Cash test on the growth plan: ___

## Decisions
| Decision | Door | Decider | Decide by | Check on |
|---|---|---|---|---|

## Bets
| Bet | Odds | Payoff | Stop signal | Double-down signal |
|---|---|---|---|---|
- Failure budget this year: ___%

## Standards
- Domain: ___ · What good looks like: ___ · Realistic scope: ___

## This quarter
1. [Action] · owner · [source]
2. ...
3. ...

## Where to be careful
- [Translations from Amazon's scale; points resting on one interview rather than a letter; where his view
  changed over time]
```

Rules for the notes:
- **At most three actions**, each with an owner.
- **One red defense fixed per quarter.** Not all four at once.
- **Every two-way door gets a deadline in days**; every one-way door gets a named senior owner.
- **Mark every application** to the user's company as our reading.

Templates: `templates/01-day-2-audit.md`, `templates/02-working-backwards-brief.md`,
`templates/03-door-decision-log.md`, `templates/04-high-standards-checklist.md`,
`templates/05-experiment-and-failure-budget.md`, `templates/06-hiring-bar.md`,
`templates/07-proxy-and-input-audit.md`, `templates/08-regret-minimization.md`. A full example:
`examples/01-worked-session.md`.
