---
name: hiring-round-review
description: Drafts or checks a review of one completed hiring round in aggregate, covering time at each stage, drop-off between stages, the share of candidates who got an answer and how fast, score spread by interviewer shown by letter to check consistency and calibration, equality monitoring in aggregate only with a small-numbers warning, and what to change next round, under UK practice. Use when a talent acquisition lead, talent acquisition partner or HR adviser asks for a hiring round review, a recruitment campaign review, a post-hire review, a look back at a recruitment round, hiring metrics for one vacancy, a time-to-hire breakdown, an interviewer calibration check, or a check of a round review before it goes to the hiring manager or Head of People.
---

# Hiring Round Review

Looks back at one finished hiring round in numbers: how long each stage took, where candidates dropped out, how many got an answer and how fast, how consistently the interviewers scored, and what the equality monitoring shows in aggregate. It ends with what to change next round. Or checks a review someone has drafted. It turns an ATS export into two pages a hiring manager will read before the next round opens.

## When to use

- "We've just filled the two developer roles. Can you pull together a review of the round?"
- "Here's the ATS export. Where did we lose people?"
- "One interviewer's scores look high. Can we check calibration across the panel?"
- "Check my round review before it goes to the Head of People."
- "What should we change before we run this vacancy again?"

Wrong tool for anything about one candidate or one hire (use Decision Record), or for asking candidates what it was like (use Candidate Experience Survey, then bring its results here).

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the round's numbers from the ATS: candidates at each stage, dates or days at each stage, withdrawals and the stage people left at, and when each group was told its outcome.
2. **Essential:** scores by interviewer and criterion, with interviewers as letters and candidates as letters or removed. [any names are replaced with letters before the data is used]
3. The equality monitoring summary, as counts by stage from the separate monitoring form. [left out]
4. What to compare against. [your previous round of the same vacancy, if you have one; no outside benchmarks]
5. Candidate Experience Survey results, in aggregate. [none]
6. Who reads it. [the hiring manager and the talent acquisition lead]

Never ask for candidate or interviewer names, individual equality monitoring answers, or monitoring data joined to scores or outcomes. If any of it arrives, leave it out of the review and say so.

## Steps

Numbers in square brackets in these steps and the Quality checks are defaults. Use the user's own figure if they give one; otherwise use the default without asking.

1. Read what the user has given, including attachments. If they've given a draft review, this is a check job: check every figure and claim against the data in the draft and any export, run the Quality checks, list each problem with where it sits and why it matters, then write a corrected review.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If the user says "just draft it", use what's there, leave a placeholder for each missing figure, and list the assumptions.
3. Clean the data before any analysis. Replace interviewer names with letters (Interviewer A, B, C) and candidate names with letters, or drop candidate rows where counts will do. The key stays with the TA team, outside the review. If equality monitoring arrives per candidate, or joined to scores, interviewers or outcomes, set that table aside unused and ask for counts by stage from the separate monitoring summary.
4. Time at each stage: the median working days and the range for application to screening decision, screening to first interview, first interview to decision, final interview to offer, and offer to acceptance, plus application to offer overall. Use the median, because one slow case drags an average. Name the longest wait.
5. Drop-off: the count at each stage, the share going on as n of N (recalculated from the counts), and withdrawals by stage with any recorded reasons. Withdrawals between invitation and interview point at the invitation and scheduling; withdrawals after interview point at the wait or the offer.
6. Answers: for each stage, how many candidates were told their outcome, how many weren't, and the median working days to hear, against the timescale they were promised. Anyone who heard nothing is the first thing to fix. Check every sentence about answers against these counts.
7. Score spread by interviewer: for each interviewer letter, the number of candidates scored, their median and range on each criterion, and how often their score sat [two] or more points from the panel's agreed score. Look for an interviewer scoring consistently high or low, a criterion with a wide spread (its anchors need work), and scores bunched in the middle of the scale. Write these as calibration prompts for the whole panel, to work through with the Scoring Guide and the Interviewer Briefing, and name no interviewer as lenient or harsh. Where an interviewer scored fewer than [five] candidates, show the figures and label them too few to read.
8. Equality monitoring, only from the aggregate summary: the count of each group at application, interview and offer. Show a figure only where the group has [10] or more people at that stage; otherwise write "fewer than 10", and hide any other figure that would let a reader work it out by subtraction. Add the small-numbers warning: in groups this size, one or two people can make a difference that means nothing, so record it as something to watch across several rounds and draw no conclusion about a stage or a test from it. Where a pattern holds over several rounds, look first at the process (the criteria, the questions, the task, the panel). Positive action under sections 158 and 159 of the Equality Act 2010 is narrow, and section 159 applies only between candidates who are as qualified as each other; point the user to advice before using either.
9. What to change next round: three to five changes, each tied to a finding in the review, with an owner by role and a date. Put candidates left without an answer first, then calibration, then time and drop-off.
10. Run the Quality checks below and fix what fails before showing anything.
11. Present the review, then a short **Assumptions** list and a **Check before you use it** list: that the figures match the ATS export, that the interviewer key is held only by the TA team, who the review will be shared with, and that the monitoring summary came from the separate form.
12. Offer a .docx, a one-slide summary, the Scoring Guide or Interviewer Briefing skills for calibration fixes, or the Not Progressing Email skill for gaps in answers.

## Output format

**Hiring round review: [vacancy], [dates]**
For: [audience]. Prepared by: [role]. Date: [date].

**Summary**: [three sentences at most: the round in numbers, the biggest problem, the first change]

**1. The round in numbers**

| Stage | Candidates | Went on (n of N) | Withdrew | Median working days at this stage (range) |
| --- | --- | --- | --- | --- |

Application to offer: median [n] working days (range [n] to [n]).

**2. Did candidates get an answer?**

| Stage stopped at | Candidates | Told their outcome | Not told | Median working days to hear | Promised |
| --- | --- | --- | --- | --- | --- |

**3. Scoring consistency** (interviewers by letter; the key stays with the TA team)

| Interviewer | Candidates scored | Median on [criterion 1] | Median on [criterion 2] | Times [2]+ points from the agreed score |
| --- | --- | --- | --- | --- |

[Two or three sentences of calibration prompts for the panel, with any interviewer under [five] candidates labelled too few to read.]

**4. Equality monitoring** (aggregate counts from the separate monitoring summary)

| Group | Applied | Interviewed | Offered |
| --- | --- | --- | --- |

Small numbers: [the warning in one or two sentences]. Figures under [10] show as "fewer than 10".

**5. What candidates told us**: [survey results in aggregate, with the base, or "no survey this round"]

**6. What to change next round**

| Change | Finding it answers | Owner (role) | By |
| --- | --- | --- | --- |

Two pages. On a check job, the list of problems comes first and sits outside the two pages.

## Try it

`examples/brackenholt-developer-round-review.md` is a draft review of the Software Developer round at Brackenholt Energy, a fictional 900-person energy supplier that has just filled two remote developer roles, with problems planted in it. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before rewriting the review. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-hiring-interviews), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- No candidate or interviewer is named anywhere: candidates appear as counts or letters, interviewers as letters, and the key isn't in the review.
- Every figure comes from the user's data with its base (n of N), and every percentage is recalculated from its counts.
- Time at each stage is a median with its range, and section 2 shows for every stage how many candidates were told their outcome, how many weren't, and how fast. Every claim about answers matches those counts.
- No conclusion rests on a group smaller than [10] or on an interviewer who scored fewer than [five] candidates; such figures are labelled too few to read, and equality monitoring figures under [10] are hidden.
- Equality monitoring appears only as aggregate counts by stage from the separate summary, never beside individual candidates, scores, interviewers or outcomes.
- Score differences are written as calibration prompts for the whole panel; no interviewer is rated, ranked or taken off a panel on the strength of the review.
- The review ends with three to five changes, each tied to a finding, with an owner by role and a date.

## Guardrails

- The one rule for this pack: Claude drafts the questions, guides and letters. Interviewers gather the evidence, and people make every hiring decision. This review describes a process and groups of people. It never reopens or comments on a decision about one candidate and never judges one interviewer; anything about one person's interviewing goes to them privately from the TA lead, as support, and stays out of the review.
- Personal data: ATS exports hold personal data under UK GDPR and the Data Protection Act 2018. Remove names, candidate references and contact details before pasting anything in, work from counts wherever counts will do, and follow your organisation's AI policy and the ICO's guidance on keeping recruitment records.
- Fairness: equality monitoring data is special category data under UK GDPR. Keep it apart from selection, use it only in aggregate to monitor equality of opportunity, and never join it to scores, interviewers or outcomes. Never infer a protected characteristic from names, photos, CVs or anything else. Where one group fares worse, look first at the process, under the Equality Act 2010's tests for direct and indirect discrimination.
- Law: this follows the Equality Act 2010 (including sections 158 and 159 on positive action), the EHRC Employment Statutory Code of Practice, UK GDPR, the Data Protection Act 2018 and ICO guidance. Check the current versions and your own policy. This review is a draft, never legal advice; take advice before acting on a pattern in the monitoring data.
- No invented facts: every number comes from the user's data or stays as a placeholder. Never estimate a figure to fill a gap, and never add an outside benchmark.
