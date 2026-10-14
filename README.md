# Jeff Bezos' Day 1 Playbook (Unofficial)

**An unofficial, fully sourced playbook and AI skill that runs Jeff Bezos' Day 1 methods (the Day 2 audit,
customer obsession and working backwards, one-way and two-way doors, high standards, experiments and big bets,
resisting proxies, the hiring bar, the flywheel, six-page memos and regret minimization) on your company, team
or decision. Built only from his own words: 24 letters to Amazon shareholders and three long interviews.**

Jeff Bezos founded Amazon in 1994 and was its CEO until 2021. Every year from 1997 to 2020 he wrote a letter to
shareholders, and Amazon filed each one with the SEC. Together they are the most complete record any founder has
left of how he says he ran a company: what to measure, how to decide, how to invent and fail, how to hire, and
why it should always be Day 1. This repo turns those letters, plus his 2001 Academy of Achievement interview,
his 2018 Economic Club of Washington interview and his 2023 Lex Fridman interview, into methods you can run on
your own company this week.

> "Day 2 is stasis. Followed by irrelevance. Followed by excruciating, painful decline. Followed by death. And
> that is why it is always Day 1."
> Jeff Bezos, letter to shareholders (2016) [L2016]

> ⚠️ **Unofficial.** Not written, reviewed or endorsed by Jeff Bezos, Amazon or anyone connected to them, and
> not affiliated with Amazon. It's a structured guide in our own words, with short credited quotes and a link to
> every source. It covers building and running companies, and one framework for personal decisions: no
> politics, no private life.

---

## What's inside

### The playbook

| # | Chapter | What you'll learn |
|---|---|---|
| 00 | [Who he is, for this playbook](references/00-who-is-jeff-bezos.md) | A timeline from the sources · how to weigh each source · what to borrow and what not to |
| 01 | [Day 1 vs Day 2](references/01-day-1-vs-day-2.md) | How *Day 1* changed from 1997 to 2023 · the four defenses · tenets *unless you know a better way* · the Day 2 audit |
| 02 | [Customer obsession and working backwards](references/02-customer-obsession-and-working-backwards.md) | Afraid of customers, not competitors · working backwards vs skills forward · listen and invent · the working-backwards brief |
| 03 | [What won't change, and long-term thinking](references/03-what-wont-change-and-long-term-thinking.md) | The ten-year question · owners, not tenants · the quarter three years out · the stable-needs map |
| 04 | [Free cash flow, inputs and outputs](references/04-cash-flow-inputs-and-outputs.md) | Cash flow over earnings · the 2004 machine example · 452 goals and inputs · the stock is not the company |
| 05 | [One-way and two-way doors](references/05-one-way-and-two-way-doors.md) | Type 1 and Type 2 · 70% of the information · disagree and commit · escalation vs stamina · the door log |
| 06 | [High standards](references/06-high-standards.md) | Teachable, domain specific, recognize, scope · root causes · paper cuts |
| 07 | [Invention, failure and big bets](references/07-invention-failure-and-big-bets.md) | 10% at 100x · failure that scales · wandering · protecting new ideas · the experiment portfolio |
| 08 | [Resist proxies, and tell the truth](references/08-resist-proxies-and-tell-the-truth.md) | Process, surveys and metrics as proxies · anecdotes vs data · speak last · the proxy audit |
| 09 | [Hiring and the bar](references/09-hiring-and-the-bar.md) | The three 1998 questions · from hiring to standards · missionaries vs mercenaries |
| 10 | [The flywheel and scale economics](references/10-the-flywheel-and-scale-economics.md) | The 2001 loop · customer experience as a fixed cost · the flywheel, named in 2014 · the loop map |
| 11 | [Memos, not slides](references/11-memos-not-slides.md) | Six-page narratives · study hall · crisp document, messy meeting · two kinds of meeting |
| 12 | [Regret minimization](references/12-regret-minimization.md) | Age 80 (later 90) · omission vs commission · realistic odds · passion vs the gold rush |
| 13 | [Differentiation, and creating more than you consume](references/13-differentiation-and-creating-more-than-you-consume.md) | The 2020 value ledger · *me too* · don't out-book the book · the universe wants you to be typical |

### Templates

| Template | Use it to |
|---|---|
| [01 Day 2 audit](templates/01-day-2-audit.md) | Score the four Day 1 defenses and pick one to fix this quarter |
| [02 Working-backwards brief](templates/02-working-backwards-brief.md) | Start a product from the customer, check the ten-year need, and run the differentiation test |
| [03 Door decision log](templates/03-door-decision-log.md) | Sort decisions into one-way and two-way doors, assign deciders and deadlines, settle disagreements |
| [04 High-standards checklist](templates/04-high-standards-checklist.md) | Recognize, scope, skill and teach a standard in one domain, plus a six-page memo check |
| [05 Experiment and failure budget](templates/05-experiment-and-failure-budget.md) | Size every bet, set stop and double-down signals, and decide what you're willing to lose |
| [06 Hiring bar](templates/06-hiring-bar.md) | Rank against the team and debrief with the three questions and the missionary test |
| [07 Proxy and input audit](templates/07-proxy-and-input-audit.md) | Check each metric's truth, rewrite goals as inputs, and run the cash test on growth |
| [08 Regret minimization](templates/08-regret-minimization.md) | Work through a personal one-way door from age 80 |

### Worked example

[A full session, start to finish](examples/01-worked-session.md): a fictional veterinary-software company with
invented numbers, run through the whole skill. Three of four Day 1 defenses were red; decision time on two-way
doors fell from 24 days to 4.

---

## How to use this

### 1. Run it as an AI skill (10 minutes)

**Install** into your agent's skills folder. For Claude Code:

```bash
git clone https://github.com/01ayushgarg/jeff-bezos-day-one-playbook \
  ~/.claude/skills/jeff-bezos-day-one-playbook
```

If your agent doesn't read skill folders, paste `SKILL.md` into the chat and attach the chapters it asks for.

**Then ask for a Day 1 review.** Copy and fill in:

```text
Run a Jeff Bezos-style Day 1 review on my company.

What we do, and for which customer (one sentence):
Who pays or decides but isn't the customer:
What we shipped last quarter, and where each idea came from:
The metrics leadership reviews every week:
Open decisions, and how long each has been waiting:
Bets and experiments running now, and what each costs:
What makes us different (one line):
Size, stage, months of cash:
```

**You get back:** a Day 2 audit with the four defenses scored, the stable needs your customers will still have
in ten years, your goals rewritten as inputs and a cash test on your growth plan, every open decision sorted
into one-way and two-way doors with a decider and a deadline, your bets with stop and double-down signals and a
failure budget, a standards check on the domain that matters most, three actions for this quarter, and where to
be careful. Every point cites the letter or interview it comes from.

**Other things you can ask:**
- *Is this a one-way or a two-way door? Who should decide it?*
- *We disagree on this. Disagree and commit, or escalate?*
- *Write this product brief working backwards from the customer.*
- *Which of our metrics are proxies?*
- *Size our experiments and set a failure budget.*
- *Is this candidate going to raise the bar?*
- *Turn this slide deck into a six-page memo outline.*
- *I'm thinking of leaving my job to start a company. Run regret minimization with me.*

### 2. Use the templates (30 minutes, no AI)

1. [Day 2 audit](templates/01-day-2-audit.md) once a quarter, or when someone says *we used to be faster*.
2. [Working-backwards brief](templates/02-working-backwards-brief.md) before any new product or major feature.
3. [Door decision log](templates/03-door-decision-log.md) every week.
4. [High-standards checklist](templates/04-high-standards-checklist.md) when quality is uneven, and before an
   important memo.
5. [Experiment and failure budget](templates/05-experiment-and-failure-budget.md) once a year, and when a new
   bet starts.
6. [Hiring bar](templates/06-hiring-bar.md) before you open a key role.
7. [Proxy and input audit](templates/07-proxy-and-input-audit.md) when you set goals, and when the metrics look
   fine but customers complain.
8. [Regret minimization](templates/08-regret-minimization.md) before a big personal decision.

### 3. Read it

Start with chapter 01 if the company feels slow, 02 if the roadmap follows competitors, 05 if decisions are
stuck, 07 if nothing new is being tried, 08 if the metrics and the customers disagree, 11 if meetings run on
slides, and 12 if the decision is your own. Every chapter ends with a short method in our own words: steps, a
worked example, failure modes and limits, all labelled as our reading.

**His own caveat:** "We never claim that our approach is the right one – just that it's ours" [L2015]. Use the
tests, not his scale.

---

## How it stays honest

- **First-party only:** his 24 shareholder letters as filed with the SEC, and three interviews from the
  publishers' own transcripts (lexfridman.com, achievement.org, economicclub.org). No biographies, no
  books about Amazon, no listicles of *Bezos rules*.
- **Speakers are checked:** only his words are quoted. Customers, a coach, Benjamin Graham and Richard Dawkins
  appear inside his letters; Lex Fridman, David Rubenstein and the Academy's editors appear in the interviews.
  None of them is quoted as Bezos.
- **Only his letters:** the 2021 and later shareholder letters are Andy Jassy's and aren't used.
- **Famous lines that aren't in the sources are left out:** *your margin is my opportunity*, *good intentions
  don't work, mechanisms do*, *two-pizza teams*, the *bar raiser*, the press release and FAQ format, and the
  short *stubborn on vision, flexible on details* (his own longer 2020 wording is quoted instead). See
  `SOURCES.md`.
- **What was checked:** a script extracted every quoted passage and blockquote in this repo (232 of them) with
  the source ID cited for it, and confirmed each one is an exact substring of that source's text, allowing only
  quote-mark, dash and whitespace differences, with three dots marking trims. For interviews it also confirmed
  the words are in Bezos's own turns and, for the Lex Fridman transcript, at the cited timestamp. All passed.
  The text copies are the publishers' copyright and aren't shipped, so the check can't be rerun from this repo;
  every quote has a source ID and a link so you can check it by hand.
- **Short quotes, more paraphrase:** no quote is over 60 words, and no source is quoted at more than about a
  tenth of its length (the highest is under 8% of the 2016 letter). Longer passages are paraphrased and cited.
- **Change over time is shown, not smoothed:** what Day 1 means (1997 to 2023), growth versus cash flow,
  hiring versus standards, physical stores (2006 versus 2018), analysis versus heart. See the conflicts list in
  `SOURCES.md`.
- **Our own reading is marked**, never presented as his words.

### Known limits

- **One company's view.** The letters are written by the CEO to shareholders. They argue for Amazon's approach;
  survivorship bias applies to every success story in them.
- **Scale.** Most examples come from a very large company. The steps, thresholds and budgets in this playbook
  are ours, sized for smaller teams, and should be judged on whether they help.
- **Interview transcripts.** The Lex Fridman transcript is human-made and may contain errors; the Economic Club
  transcript is edited. Quotes are exact to the published text.
- **Thin spots.** The proxy, anecdote and meeting material leans on the 2023 interview; the regret framework
  rests on two interviews (2001 and 2018).
- **Figures** are his, as of each letter's date, and weren't checked independently.

## Sources

The full list, with dates and links, is in [`SOURCES.md`](SOURCES.md):

Letters to Amazon shareholders, 1997 to 2020 (24 letters, from Amazon's SEC filings) · Academy of Achievement
interview (2001) · Economic Club of Washington interview with David Rubenstein (2018, the Club's edited
transcript) · Lex Fridman Podcast #405 (2023, lexfridman.com transcript).

## License

- **Our text** (chapters, skill, templates, structure): [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
- **Quotes** remain Jeff Bezos' words and their publishers'. They're short, credited excerpts for commentary and
  are **not** covered by this license.

See [`LICENSE`](LICENSE).

## Corrections

Spot a misquote, a mislabelled speaker or a broken link? Open an issue with the source ID and the passage.
