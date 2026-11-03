---
name: work-sample-task
description: Drafts or checks a work sample task for one role, a short exercise that mirrors real work and is hard to fake, with a candidate brief, a short stated time limit, a live follow-up where the candidate explains their choices, adjustments, and a marking guide tied to the role's criteria. Use when a talent acquisition partner, recruiter, HR adviser or hiring manager asks for a work sample, practical assessment, take-home task, technical test, coding exercise, written exercise, in-tray exercise, presentation task or role play for an interview, asks how to make a task harder to fake with AI, or wants an existing assessment task checked.
---

# Work Sample Task

Produces a short task that mirrors a real piece of the job: the brief the candidate gets, a live follow-up where they explain their choices, the adjustments on offer and a marking guide tied to the role's criteria. Or checks a task someone already sets. Candidates show what they can do in a set time, and markers judge every piece of work against the same guide.

## When to use

- "Design a take-home coding task for a remote developer, with a marking guide."
- "We want a practical assessment for field engineers that takes under an hour."
- "Write an in-tray exercise for the finance business partner final interview."
- "Candidates are pasting AI answers into our written task. How do we redesign it?"
- "Check our take-home before we send it to the next candidate."

Wrong tool for the rules on AI use across the whole process (use the Candidate AI Use Statement), for checks on stand-in candidates (use the Interview Integrity Plan) or for the rating scale behind interview questions (use the Scoring Guide).

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the role and the one to three criteria the task should test, from the role's success profile. [criteria proposed by Claude from the job description, marked for you to confirm]
2. **Essential:** what someone in the job really does in their first few months that the task could mirror. [Claude proposes two options for you to choose from]
3. Where it's done: take-home before the interview, or during the interview. [during the interview: 30 minutes, then a 15-minute live follow-up]
4. What your organisation allows on AI tools, and whether candidates are paid for their time. [the rule from your Candidate AI Use Statement; time unpaid]
5. Who marks it, by role. [two markers, each marking alone first]

Never ask for real customer, client or employee data to build the task from, or for anything about a particular candidate.

## Steps

Numbers in square brackets in these steps and the Quality checks are defaults. Use the user's own figure if they give one; otherwise use the default without asking.

1. Read what the user has given, including any job description, success profile or existing task. If they've given an existing task, this is a check job: run the Quality checks on it, list every problem with the part of the brief or marking guide where it sits and why it matters, then write a corrected task that keeps their idea where it works.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If the user says "just draft it", proceed on the defaults and list them as assumptions.
3. Choose the slice of work. Pick one task the job holder really does, small enough to finish in the time: a small code change with tests and a note on it, a reply to a customer complaint, a set of figures to explain to a budget holder, a fault to find on a training rig, a call role play. Test the one to three criteria that a task shows better than interview questions do, and leave the rest to the interview.
4. Build it on a made-up problem with made-up data: a fictional customer, an invented dataset, a practice codebase, a problem the team solved long ago. Never set work the organisation would use or profit from, such as a live backlog item, a real campaign or a real client's figures, and say so in the brief. Keep all real data out, because candidates' work travels through email and personal devices.
5. Keep the time short and state it. For a take-home, [90] minutes of work, with [five] working days to fit it in; during the interview, [30 to 45] minutes. Say in the brief how long it should take, whether the time is paid, and that extra polish or extra features earn no marks. An open-ended task favours candidates with free evenings and weekends, which can put carers and some disabled candidates at a disadvantage, so a short, fixed limit is the fairer design.
6. Add the live element: [15] minutes in which the candidate talks a marker through the work. Write three set questions, the same for everyone: why they made one key choice, what they'd do next with more time, and one planned change to the brief ("The customer replies that they can't pay until the 28th. What would you change?"). Explaining and adapting in the moment shows the candidate's own thinking, so a task written by someone else, or by an AI tool, helps them less. The live element is marked as part of the task.
7. State the AI rule in one or two sentences from the user's Candidate AI Use Statement, the same for every candidate. [Default: use the tools you'd use in the job, and tell us which you used.] Never accuse a candidate of using AI. Any concern goes through the Interview Integrity Plan, applied the same way to everyone.
8. Write the marking guide. For each criterion, say what the marker looks for in the work and in the live follow-up, with short descriptions of weak, sound and strong work that anyone could check ("handles a second failed payment and says why"). Mark only the criteria; spelling, layout and polish count only where they're part of a criterion. Two markers mark alone and record their marks before they compare. Use the Scoring Guide for the full anchored scale.
9. Write the adjustments line: how to ask, by when, and examples (extra time, a different format, screen-reader-friendly files, breaks, the live questions in writing, a quiet room). No one has to give a diagnosis to ask; use the Adjustment Request Reply to answer. For a practical task, say what equipment and safety kit is provided and who supervises.
10. Write the brief: what to do, what they're given, how long it should take and the deadline, how to send it, the criteria it's marked on, the live follow-up, the AI rule, adjustments, and that the work is used only to assess them and deleted after [your retention period].
11. Run the Quality checks below and fix what fails before showing anything.
12. Present the task, then **Assumptions** and **Check before you use it**: someone in the team has done the task and it fits the time, the AI rule matches your statement, the retention period matches your policy, and nothing in the task is live work.
13. Offer a .docx, the Candidate AI Use Statement to go with it, or the Scoring Guide to anchor the marks.

## Output format

**Work sample task: [role]**, [take-home or during the interview]
Tests: [criteria]. Time: [minutes], plus a [minutes]-minute live follow-up. Markers: [roles].

**1. Candidate brief** (one page)
- The task: [two or three sentences]
- What you'll get: [files, data, access, all made up]
- Time: about [minutes], [paid or unpaid]. Extra time or polish earns no extra marks.
- Deadline and how to send it: [date or window], [route]
- How it's marked: [the criteria in plain words]
- Live follow-up: [minutes] talking us through your work, [format]
- AI tools: [rule]
- Adjustments: [how to ask, by when, examples]
- Your work: [this is a made-up problem; we use your work only to assess you and delete it after (period)]

**2. Live follow-up questions** (the same for every candidate)
1. "[why one key choice]" 2. "[what next with more time]" 3. "[planned change]"

**3. Marking guide**
| Criterion | Look for, in the work and the follow-up | Weak | Sound | Strong |
| --- | --- | --- | --- | --- |

Each marker marks alone and records marks before comparing. Notes record what was in the work and what the candidate said.

**4. Set-up notes** (for the TA team): materials to prepare, the timing check, how adjustments are handled, where work is stored and when it's deleted.

Two pages at most.

## Try it

`examples/brackenholt-developer-take-home.md` is an engineering manager's draft take-home task for the remote Software Developer vacancy at Brackenholt Energy, a fictional 900-person energy supplier, with problems planted in it. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before writing the corrected task. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-hiring-interviews), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- The task mirrors a real piece of the job, and every row of the marking guide maps to a named criterion. Nothing marks overall impression, likeability or "fit".
- The time is short and stated ([90] minutes take-home, [45] during the interview), and the brief says whether the time is paid and that extra time or polish earns no marks.
- The task uses a made-up or long-solved problem and made-up data. Nothing in it is live work the organisation would use or profit from, and the brief says so.
- There's a live follow-up with three set questions, including one planned change, the same for every candidate, and it's marked.
- The brief states the AI rule and how to ask for adjustments, with examples.
- Every candidate gets the same brief, materials, time and marking guide, and markers mark alone before comparing.

## Guardrails

- The one rule for this pack: Claude drafts the questions, guides and letters. Interviewers gather the evidence, and people make every hiring decision. Claude drafts the task, the brief and the marking guide. Markers look at each candidate's work and record marks against the guide, and the panel decides. Claude never marks a candidate's work.
- Personal data: a candidate's submission and the marks on it are personal data under UK GDPR and the Data Protection Act 2018. The candidate can ask to see them through a subject access request. Store them where your other recruitment records live, keep them only as long as your retention policy and the ICO's guidance on recruitment records allow, and follow your organisation's AI policy. Real customer or employee data never goes in a task.
- Fairness: every candidate gets the same task, time and marking. Never infer or mention protected characteristics. Check the brief for jargon that favours insiders and for assumptions about who has spare time or paid software.
- Law: under the Equality Act 2010 (England, Scotland and Wales; Northern Ireland has its own equality law), section 20 can require adjustments to the task, such as extra time or a different format, and a long unpaid task that puts carers or disabled candidates at a disadvantage risks indirect discrimination unless it can be justified. See the EHRC Employment Statutory Code of Practice. Check the current versions. This is a draft, never legal advice.
- No invented facts: criteria, times, rules and retention periods come from the user or stay as placeholders.
