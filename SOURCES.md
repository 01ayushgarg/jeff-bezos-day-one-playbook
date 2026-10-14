# Sources

Every quote in this repo is from one of the sources below. How quotes were checked: we saved a plain-text copy
of each source (the letters from Amazon's SEC filings, the interviews from the publishers' own pages) and ran a
script that extracts every quoted passage and blockquote from every file in this repo, together with the
source ID cited for it, and confirms that the passage is an exact substring of that specific source, allowing
only quote-mark, dash and whitespace differences, with three dots marking any trim. For the interviews, the
script also confirms the passage is inside Bezos's own turns (not the interviewer's), and for `[LEX405]` that
it sits at the cited timestamp. It flags any quote over 60 words and measures how much of each source is
quoted (the share of Bezos's own words in that source that appear in quotes here). The text copies aren't
shipped in this repo (they're the publishers' copyright), so the check can't be rerun from the repo alone; the
links let you check any quote by hand.

## How citations work

### His letters to Amazon shareholders, 1997 to 2020

Each ID is the year the letter covers; it was filed with the SEC the following spring. Section headings and
the signature are part of the text. Later letters attach a reprint of the 1997 letter; our copies cut that
reprint, so 1997 wording is always cited as `[L1997]`.

| ID | Source | Date | Link |
|---|---|---|---|
| `[L1997]` | Letter to shareholders for 1997. Text of the SEC filing (annual report to security holders) | Filed 1998 | [sec.gov](https://www.sec.gov/Archives/edgar/data/1018724/000089102098000600/0000891020-98-000600.txt) |
| `[L1998]` | Letter to shareholders for 1998. Text of the SEC filing (annual report to security holders) | Filed 1999 | [sec.gov](https://www.sec.gov/Archives/edgar/data/1018724/000089102099000637/0000891020-99-000637.txt) |
| `[L1999]` | Letter to shareholders for 1999. Text of the SEC filing (annual report to security holders) | Filed 2000 | [sec.gov](https://www.sec.gov/Archives/edgar/data/1018724/000089102000000646/0000891020-00-000646.txt) |
| `[L2000]` | Letter to shareholders for 2000. Text of the SEC filing (8-K Exhibit 99.1) | Filed 2001 | [sec.gov](https://www.sec.gov/Archives/edgar/data/1018724/000103221001500339/dex991.txt) |
| `[L2001]` | Letter to shareholders for 2001. Text of the SEC filing (8-K Exhibit 99.1) | Filed 2002 | [sec.gov](https://www.sec.gov/Archives/edgar/data/1018724/000103221002000654/dex991.txt) |
| `[L2002]` | Letter to shareholders for 2002. Text of the SEC filing (annual report to security holders) | Filed 2003 | [sec.gov](https://www.sec.gov/Archives/edgar/data/1018724/000089102003001186/v89126exv99w1.htm) |
| `[L2003]` | Letter to shareholders for 2003. Text of the SEC filing (8-K Exhibit 99.1) | Filed 2004 | [sec.gov](https://www.sec.gov/Archives/edgar/data/1018724/000119312504060718/dex991.htm) |
| `[L2004]` | Letter to shareholders for 2004. Text of the SEC filing (8-K Exhibit 99.1) | Filed 2005 | [sec.gov](https://www.sec.gov/Archives/edgar/data/1018724/000119312505070440/dex991.htm) |
| `[L2005]` | Letter to shareholders for 2005. Text of the SEC filing (8-K Exhibit 99.1) | Filed 2006 | [sec.gov](https://www.sec.gov/Archives/edgar/data/1018724/000119312506084815/dex991.htm) |
| `[L2006]` | Letter to shareholders for 2006. Text of the SEC filing (8-K Exhibit 99.1) | Filed 2007 | [sec.gov](https://www.sec.gov/Archives/edgar/data/1018724/000119312507093886/dex991.htm) |
| `[L2007]` | Letter to shareholders for 2007. Text of the SEC filing (8-K Exhibit 99.1) | Filed 2008 | [sec.gov](https://www.sec.gov/Archives/edgar/data/1018724/000119312508084145/dex991.htm) |
| `[L2008]` | Letter to shareholders for 2008. Text of the SEC filing (8-K Exhibit 99.1) | Filed 2009 | [sec.gov](https://www.sec.gov/Archives/edgar/data/1018724/000119312509081096/dex991.htm) |
| `[L2009]` | Letter to shareholders for 2009. Text of the SEC filing (8-K Exhibit 99.1) | Filed 2010 | [sec.gov](https://www.sec.gov/Archives/edgar/data/1018724/000119312510082914/dex991.htm) |
| `[L2010]` | Letter to shareholders for 2010. Text of the SEC filing (8-K Exhibit 99.1) | Filed 2011 | [sec.gov](https://www.sec.gov/Archives/edgar/data/1018724/000119312511110797/dex991.htm) |
| `[L2011]` | Letter to shareholders for 2011. Text of the SEC filing (8-K Exhibit 99.1) | Filed 2012 | [sec.gov](https://www.sec.gov/Archives/edgar/data/1018724/000119312512161812/d329990dex991.htm) |
| `[L2012]` | Letter to shareholders for 2012. Text of the SEC filing (8-K Exhibit 99.1) | Filed 2013 | [sec.gov](https://www.sec.gov/Archives/edgar/data/1018724/000119312513151836/d511111dex991.htm) |
| `[L2013]` | Letter to shareholders for 2013. Text of the SEC filing (8-K Exhibit 99.1) | Filed 2014 | [sec.gov](https://www.sec.gov/Archives/edgar/data/1018724/000119312514137753/d702518dex991.htm) |
| `[L2014]` | Letter to shareholders for 2014. Text of the SEC filing (8-K Exhibit 99.1) | Filed 2015 | [sec.gov](https://www.sec.gov/Archives/edgar/data/1018724/000119312515144741/d895323dex991.htm) |
| `[L2015]` | Letter to shareholders for 2015. Text of the SEC filing (8-K Exhibit 99.1) | Filed 2016 | [sec.gov](https://www.sec.gov/Archives/edgar/data/1018724/000119312516530910/d168744dex991.htm) |
| `[L2016]` | Letter to shareholders for 2016. Text of the SEC filing (8-K Exhibit 99.1) | Filed 2017 | [sec.gov](https://www.sec.gov/Archives/edgar/data/1018724/000119312517120198/d373368dex991.htm) |
| `[L2017]` | Letter to shareholders for 2017. Text of the SEC filing (8-K Exhibit 99.1) | Filed 2018 | [sec.gov](https://www.sec.gov/Archives/edgar/data/1018724/000119312518121161/d456916dex991.htm) |
| `[L2018]` | Letter to shareholders for 2018. Text of the SEC filing (8-K Exhibit 99.1) | Filed 2019 | [sec.gov](https://www.sec.gov/Archives/edgar/data/1018724/000119312519103013/d727605dex991.htm) |
| `[L2019]` | Letter to shareholders for 2019. Text of the SEC filing (8-K Exhibit 99.1) | Filed 2020 | [sec.gov](https://www.sec.gov/Archives/edgar/data/1018724/000119312520108427/d902615dex991.htm) |
| `[L2020]` | Letter to shareholders for 2020. Text of the SEC filing (8-K Exhibit 99.1) | Filed 2021 | [sec.gov](https://www.sec.gov/Archives/edgar/data/1018724/000110465921050346/tm216818d2_ex99-1.htm) |

### His interviews

| ID | Source | Date | Link |
|---|---|---|---|
| `[LEX405 hh:mm:ss]` | *Jeff Bezos: Amazon and Blue Origin*, Lex Fridman Podcast #405. Transcript published by lexfridman.com, which says it is human generated and may have errors. **Only lines labelled Jeff Bezos are quoted.** The timestamp is the one printed at the start of the turn in the transcript | Published Dec 2023 | [transcript](https://lexfridman.com/jeff-bezos-transcript/) |
| `[AOA01]` | Interview with the American Academy of Achievement, San Antonio, Texas. Published on the Academy's member page. **Only his answers are quoted**, not the questions, the Academy's biography, photo captions or page headlines | 4 May 2001 | [achievement.org](https://achievement.org/achiever/jeffrey-p-bezos/) |
| `[ECW18]` | Interview by David M. Rubenstein at The Economic Club of Washington, D.C. Milestone Celebration event. **The Club's edited transcript** (PDF, 30 pages). Only lines labelled Jeff Bezos or Mr. Bezos are quoted; the transcript's explanatory footnotes are the Club's | 13 Sep 2018 | [economicclub.org (PDF)](https://www.economicclub.org/sites/default/files/transcripts/Jeff_Bezos_Edited_Transcript.pdf) |

## Labelling rules

- **His words** are in quotation marks (or a blockquote) with a citation. Nothing else is.
- **Other people's words inside his letters** are never quoted as his: customers, sellers and authors (most of
  the 2011 letter), a handstand coach (2017), Benjamin Graham (2000, 2012), Richard Dawkins and a married couple's
  running joke (2020), a Kaizen expert (2008 footnote), the American Customer Satisfaction Index (2002, 2003),
  and the Amazon Leadership Principle printed in the 2017 letter. Where they matter, they are paraphrased and
  attributed.
- **Our reading**, **our suggestion** and **our paraphrase** mark our own interpretation, procedures and
  summaries.
- **`[sic]`** marks a transcription error: the Lex Fridman transcript writes *tenants* for *tenets*.
- **Dated items** carry their year. Figures are his, as of the letter's date, and haven't been checked
  independently.
- **Fictional examples** are labelled as fictional.

## Conflicts and caveats

- **What Day 1 means.** In 1997 it described the Internet being early [L1997]; from 2009 it is a sign-off
  [L2009]; in 2016 it is a culture defended against Day 2 [L2016]; in 2023 it is renewal, every day
  [LEX405 01:21:56]. Chapter 01 shows all four.
- **The cash-flow principle, restated.** The 1997 letter says "optimizing the appearance of our GAAP
  accounting" [L1997]. The 2004 letter, quoting it, drops *the appearance of our* [L2004]. The playbook quotes
  the 1997 original.
- **Growth or profit.** In 1997 Amazon chose to prioritize growth because it believed scale was central [L1997].
  The 2001 letter describes four years of growth, then nearly two of cost cutting, then a balance [L2001]. By
  2004 the ultimate measure is free cash flow per share [L2004]. Chapter 04 shows the sequence.
- **Graham's voting and weighing machine.** It is Benjamin Graham's line, which Bezos quotes in different
  wordings in 2000 [L2000], 2012 [L2012] and 2018 [ECW18]. It isn't quoted here as his; his own comments around
  it are.
- **Hiring or standards.** In 1997 and 1998, setting a high hiring bar is "the single most important element"
  of Amazon's success [L1998]. In 2017 he says high standards are teachable and the letter isn't mostly about
  hiring [L2017]. Chapter 09 shows both.
- **Listening or inventing.** In 2015, 90 to 95% of what AWS builds comes from what customers ask for [L2015];
  in 2018 the biggest needle movers are things customers don't know to ask for [L2018]. Chapter 02 reads them
  together.
- **Analysis or heart.** In 2005 math-based decisions are Amazon's favorites and judgment fills the rest
  [L2005]; in 2018 he says the most important decisions are made with instinct and heart [ECW18]. Chapter 05.
- **Physical stores.** In 2006 they failed his test for a new business, partly for lack of a differentiated
  idea [L2006]. In 2018 Amazon had cashierless stores and he said the answer had always been *yes, when
  differentiated* [ECW18, L2018]. Chapter 13.
- **How long a memo takes.** A week or more in 2017 [L2017]; up to two weeks in 2023 [LEX405 02:01:47].
- **Big winners and failed experiments.** *So many* experiments in 2015 [L2015]; *thousands* in 2018 [ECW18].
- **Regret minimization.** Age 80 in 2001 [AOA01]; he says he is moving to 90 in 2018 [ECW18]. The Academy's
  page headline says he *would* regret failing; its interview transcript says he *wouldn't*. The playbook quotes
  the transcript.
- **The odds he gave.** In 2001, he told his parents there was a 70% chance they'd lose their investment
  [AOA01]; in 2023, a 30% chance of success told to early investors [LEX405 01:19:37]. These agree.
- **Stubborn on vision.** The short line *be stubborn on vision, flexible on details* appears in our sources only
  in the host's closing words of the Lex Fridman episode, attributed to Bezos, so it isn't quoted as his. His own
  wording, in the 2020 letter, is quoted in chapter 13 [L2020].
- **Transcript quality.** `[LEX405]` is human-made with possible errors; `[ECW18]` is an edited transcript. Quotes
  are exact to the published text, including spoken slips. `[AOA01]` is the Academy's published text.
- **Letters as advocacy.** The letters are written to shareholders by the CEO. Figures are his and are dated;
  survivorship bias applies to every success story in them.

## What we didn't use, and why

- **The 2021 and later shareholder letters:** written by Andy Jassy as CEO. Not used.
- **Books:** biographies and books about Amazon, and the published anthology of his letters (we used the SEC
  texts directly). Secondary or duplicate sources.
- **Lines often attributed to him that aren't in these sources:** *your margin is my opportunity*, *good
  intentions don't work, mechanisms do*, *two-pizza teams*, the *bar raiser* role, the press release and FAQ
  format, and the short *stubborn on vision, flexible on details*. Not quoted or presented as his method.
- **Interviewers' words:** Lex Fridman, David Rubenstein and the Academy's questions and biography. Not quoted.
- **Out of scope:** passages on politics, the press and the presidency (in `[ECW18]`), liberty and the American
  Dream (in `[AOA01]`), his wealth, philanthropy and private life, the details of COVID operations (most of
  `[L2019]`), employee relations and the union vote (in `[L2020]`), and Blue Origin's engineering detail (much
  of `[LEX405]`).
- **The 2010 letter** (about Amazon's technology) is cited in no chapter; nothing in it was needed for the
  methods here.
- **Other interviews and talks:** not used, because we didn't find first-party transcripts we could check, or
  they added nothing the letters don't cover.
