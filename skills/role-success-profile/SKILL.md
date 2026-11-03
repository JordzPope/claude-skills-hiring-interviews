---
name: role-success-profile
description: Drafts or checks a role success profile for one vacancy in a UK organisation, setting four to six selection criteria from what the job involves, each with what it looks like at work, the task it comes from and how it will be assessed, agreed before the first candidate is seen, and saying which criteria an interview can't assess. Its check job flags personality traits, duplicate criteria, criteria nobody can test, culture fit, and main tasks no criterion covers. Use when a talent acquisition partner, recruiter, HR adviser or hiring manager asks for selection criteria, interview criteria, a success profile, a person specification, competencies or behaviours to interview against, what good looks like for a role, or wants a criteria list checked before interviews start.
---

# Role Success Profile

Produces the four to six criteria every candidate for one role is assessed against, each tied to a task in the job, with what it looks like at work and how it will be assessed. Or checks a criteria list someone already has. Agreed with the hiring manager before the first candidate is seen, it gives every interviewer the same picture of good, and gives the panel something specific to say in feedback.

## When to use

- "Turn this intake record into interview criteria for the engineer roles."
- "What should we be assessing for a customer adviser?"
- "Our person spec has twelve essentials. Get it down to what the job needs."
- "Check these competencies before the panel starts interviewing."
- "We use Success Profiles. Which behaviours fit this role?"

Wrong tool for writing the questions (Structured Interview Guide), the rating scales (Scoring Guide), or testing essential criteria for indirect discrimination (Essential Criteria Review).

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** what the job involves: an intake record, a job description or the hiring manager's list of main tasks.
2. **Essential:** the year-one outcomes, if they've been agreed. [taken from the job description and marked for the hiring manager to confirm]
3. The level: entry, experienced, first-line manager, specialist or senior. [as the job description suggests]
4. Any framework you use: your own competencies or values, or the UK Civil Service Success Profiles. [none; criteria in plain words]
5. What's checked outside the interview: qualifications, licences, safety assessments, vetting. [whatever the job description lists]

Never ask about the current or previous postholder, or about any candidate, and never ask for health details or protected characteristics. The profile describes the job.

## Steps

1. Read what the user has given, including attachments. If they've given an existing criteria list, person specification or competency set, this is a check job: run the Quality checks on it, list every problem with where it sits and why it matters, then write a corrected profile.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If the user says "just draft it", use the defaults and list them as assumptions.
3. List the main tasks from the inputs, putting first the ones that take most time or carry most risk, and mark any that are safety-critical or regulated. This is the job analysis that Campion, Palmer and Campion (1997) put first among the components of a structured interview: the criteria come from the work.
4. Draft four to six criteria, enough to cover the job and few enough for interviewers to keep apart. Write each as a capability or behaviour shown in a named task, so a stranger could picture it: "Explains a bill and the customer's payment options in plain words on a call." Cover every main task, and every safety-critical task above all, with a criterion or with a check outside the interview.
5. Under each criterion, write **What it looks like at work**: two or three things someone doing it well is seen or heard doing in that task. Keep them concrete; the Scoring Guide turns them into the anchors of a behaviourally anchored rating scale.
6. Test every criterion, and rewrite or cut what fails:
   - **Traits and labels** (resilient, passionate, self-starter, natural leader, "the right attitude"): ask what the manager would see the person do, in which task, and write that. If nobody can say, cut it.
   - **"Culture fit"**: never a criterion, because it invites interviewers to pick people like themselves. Find the behaviour meant (follows the safety procedure with no one watching, asks for help early) and write that.
   - **Duplicates**: two criteria an interviewer would assess with the same evidence. Merge them.
   - **Untestable**: anything nobody can assess before hiring, such as "will stay five years", "never makes mistakes" or "gets on with everyone". Cut it, or turn it into something a candidate can show now.
   - **A credential written as a criterion** ("holds a Level 3 qualification"): move it to the checks outside the interview.
7. Say how each criterion will be assessed: a behaviour question answered with STAR (situation, task, action, result), a situational question, a work sample or practical task, or a check outside the interview (certificate, licence, reference, vetting). Mark plainly every criterion an interview can't assess, and what assesses it. Interview Plan turns this column into the stage-by-stage plan.
8. Mark each criterion **essential at hire** or **can be developed after hire**, with the reason, so the panel doesn't mark someone down for what induction will teach. Send any essential that could shut out a group to Essential Criteria Review.
9. If the user works with Success Profiles, tag each criterion with its element (Behaviours, Strengths, Ability, Experience or Technical) and use the Civil Service behaviour name where one fits.
10. Run the Quality checks below and fix what fails before showing anything.
11. Present the profile, then **Assumptions** and **Check before you use it**: that the hiring manager agrees the criteria before the first candidate is seen, that the tasks match the job, any qualification a law or regulator requires, and your framework's wording.
12. Offer a .docx, Essential Criteria Review for the essentials, or Interview Plan to decide who assesses each criterion at which stage.

## Output format

**Role success profile: [job title]**
[Team, site, number of roles]. Agreed by [hiring manager role] and [TA role] on [date], before the first interview.

**Purpose of the role**: [one sentence]

**Main tasks**: [five to eight tasks, most time or risk first; safety-critical ones marked]

**Criteria** (four to six)

| # | Criterion | What it looks like at work | Task it comes from | How it's assessed | At hire or after |
| --- | --- | --- | --- | --- | --- |
| 1 | [capability or behaviour in a task] | [two or three things seen or heard] | [task] | [question type, work sample, or check outside the interview] | [essential at hire, or develop after hire, with the reason] |

**Checked outside the interview**

| Requirement | How it's checked | When |
| --- | --- | --- |
| [qualification, licence, right to work] | [certificate, licence check, Home Office right to work check] | [before offer or before start] |

**Taken out, and why**: [each trait, duplicate or untestable item removed, and what replaced it]

One page.

## Try it

`examples/brackenholt-smart-meter-engineer-profile.md` is a draft success profile for twelve Smart-Meter Engineer roles at Brackenholt Energy, a fictional 900-person energy supplier, written by a field supervisor, with problems planted in it. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before writing the corrected profile. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-hiring-interviews), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- There are four to six criteria, and each names the task it comes from.
- Every criterion is a capability or behaviour two interviewers would recognise from the same evidence; none is a trait, a label or culture fit.
- No two criteria would be assessed with the same evidence.
- Every criterion can be assessed before hiring and has a method; any an interview can't assess is marked, with what assesses it.
- Every main task, and every safety-critical task, is covered by a criterion or by a check outside the interview.
- Qualifications, licences and right to work sit under checks outside the interview.
- No wording refers to age, health, nationality or another protected characteristic, directly or through code words (young, energetic, mature, native speaker).

## Guardrails

- The one rule for this pack: "Claude drafts the questions, guides and letters. Interviewers gather the evidence, and people make every hiring decision." The profile describes the job. Interviewers gather evidence against these criteria and the panel decides who is hired; Claude never rates a candidate against them.
- Personal data: the profile needs nobody's details. Work with roles, and follow your organisation's AI policy before pasting in a job description or notes.
- Fairness: agree the criteria before the first candidate is seen and use the same ones for everyone. If they must change once interviews have started, apply the new set to every candidate, including those already seen. Never infer or mention protected characteristics. Reasonable adjustments under section 20 of the Equality Act 2010 can change how a criterion is assessed (more time, another format) while the criterion stays the same.
- Law: a criterion that puts a group sharing a protected characteristic at a disadvantage, without a job reason, risks indirect discrimination under the Equality Act 2010; see the EHRC Employment Statutory Code of Practice. This applies in England, Scotland and Wales; Northern Ireland has its own equality law. For safety-critical or regulated work, qualifications and competence follow the regulator's rules and your own procedure. Public-sector users should check their department's current Success Profiles guidance on GOV.UK. Check the current versions of everything named here. This is a draft, never legal advice.
- No invented facts: tasks, standards and qualifications come from the user or stay as placeholders.
