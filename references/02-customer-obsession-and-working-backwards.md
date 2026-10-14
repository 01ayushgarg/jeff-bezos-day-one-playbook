# 02 · Customer obsession and working backwards

> "Start with customers, and work backwards. Listen to customers, but don't just listen to customers – also
> invent on their behalf." [L2009]

## What he said

**Be afraid of customers, not competitors (1998).** "I constantly remind our employees to be afraid, to wake up
every morning terrified. Not of our competition, but of our customers." [L1998] Customers, he wrote, are loyal
"right up until the second that someone else offers them a better service." [L1998]

**Customer focus versus competitor focus (2012, 2018).** "our energy at Amazon comes from the desire to impress
customers rather than the zeal to best competitors." [L2012] He was careful not to call it the only way: there
are many successful competitor-focused companies, and he takes no view on which approach wins more often
(our paraphrase [L2012]). Out loud, in 2018, he was blunter. Many leaders he talks to are, he said, "talking
about customers, they're really focusing on competitors." [ECW18]

**Name the customer (2018).** His first step is to decide who the customer actually is. At The Washington Post,
"the customer is the reader, full stop" [ECW18]; for the preschools he was funding, the child, not the parents
or teachers [ECW18].

**Working backwards versus skills forward (2008).** "'Working backwards' from customer needs can be contrasted
with a 'skills-forward' approach where existing skills and competencies are used to drive business
opportunities." [L2008] Skills forward is useful, he says, but a company that only works that way never
develops new skills, and its old ones eventually go out of date (our paraphrase [L2008]). Kindle is his example: Amazon had never built hardware,
so it hired hardware engineers rather than shrink the vision to fit the skills it had (our paraphrase
[L2008]). The same letter ties this to durability: if a need is meaningful and durable, the company can work
patiently for years on it (our paraphrase [L2008]; see chapter 03).

**Invent before you have to (2012).** "We invent before we have to." [L2012] His examples: automatic refunds when
a video streamed badly, price protection on pre-orders, paying authors monthly when the industry paid twice a
year, and a service that tells cloud customers they're overpaying (our summary of [L2012]).

**Customers are never satisfied (2016, 2017).** "customers are always beautifully, wonderfully dissatisfied,
even when they report being happy and business is great." [L2016] A year later: "yesterday's 'wow' quickly
becomes today's 'ordinary'." [L2017]

**Listening is not enough (2015 vs 2018).** Two statements to hold together:
- 2015, about the cloud business: "90 to 95% of what we build in AWS is driven by what customers tell us they
  want." [L2015]
- 2018: "The biggest needle movers will be things that customers don't know to ask for." [L2018] And on AWS
  itself: "No one asked for AWS. No one." [L2018]

**Our reading:** these aren't a contradiction. Most of the work comes from listening; the few biggest bets come
from inventing on the customer's behalf. Plan for both, and know which one each project is.

**Long-term trust over short-term sales (2003).** Amazon let customers post negative reviews, and launched a
feature that warned you when you'd already bought an item, though it measurably cut sales (our summary of
[L2003]). The test he applied: good for customers, and good for owners "in the long run." [L2003]

**What the press release and FAQ are not.** Amazon's internal practice of writing a press release and FAQ
before building is widely described elsewhere, but it does not appear in these sources, so it isn't
presented here as his method. What the sources do support is the principle: start with the customer need and
work back to the skills and technology.

## How to apply it: the working-backwards brief (our suggestion)

Write this before any new product or major feature. The steps are ours; each idea is cited.

1. **Name the customer**, in one line, and the people who are *not* the customer even if they pay or decide
   [ECW18].
2. **Write the need** in the customer's words. Then ask: is it meaningful, and will it still matter in ten
   years? (chapter 03, [L2008])
3. **Listened or invented?** Mark whether customers asked for this, or whether you are inventing on their
   behalf [L2009, L2018]. If invented, write the evidence you have (anecdotes, observed behavior) and how you'll
   test it (chapter 07).
4. **Describe the experience** a customer will have, before any technology. What will they say *wow* about,
   and what's the *ordinary* it replaces [L2017]?
5. **Work back to the skills.** List the skills needed, mark the ones you don't have, and say how you'll get
   them. If you've shrunk the idea to fit existing skills, write down what you cut [L2008].
6. **Proactive check.** What could you do for this customer before anyone, including a competitor, forces you
   to? [L2012]
7. **The long-run test.** Name anything in the plan that is good for this quarter and bad for the customer.
   Cut it or justify it [L2003].

Use `templates/02-working-backwards-brief.md`.

## A worked scenario (fictional)

A payroll start-up wants to add an *expense cards* product because its engineers already built card
integrations: a skills-forward idea. Working backwards, the team first names the customer: the office manager
at a 20-person firm who runs payroll, not the CFO who signs the contract. Her need, from 12 interviews
(invented), is not cards but *closing the month in one afternoon instead of three days*. That need will still
matter in ten years. The brief shows the real job needs a bank-reconciliation skill the team doesn't have, so
they hire for it. The card product becomes one feature of a month-close workflow, not a standalone line.

## Failure modes and limits (our reading)

- **Saying customer, meaning competitor.** If the roadmap review spends more time on a rival's launch than on
  customer evidence, you are competitor-focused, whatever the slides say [ECW18].
- **Over-listening.** Building only what customers request gets incremental results. His biggest wins were not
  requested [L2018].
- **Over-inventing.** Inventing on behalf of customers without testing is a guess. Chapter 07 covers sizing the
  bet.
- **Wrong customer.** Optimizing for the buyer instead of the user is the commonest version of this mistake in
  B2B.
- **Limits:** his examples come from a company with tens of millions of customers and the data to match. A
  small company has fewer data points, so anecdotes count for more (chapter 08).

**Use it now:** `templates/02-working-backwards-brief.md`.

**Checks to run:**
1. Who exactly is the customer, and who only pays or decides?
2. What did you build last quarter before you had to?
3. Which roadmap item exists mainly because of a competitor?
4. What is the one thing in the plan no customer has asked for, and how will you find out if they want it?
