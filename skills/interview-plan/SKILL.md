---
name: interview-plan
description: Drafts or checks an interview plan for one vacancy in a UK organisation, with a matrix of each criterion by stage showing the method and the assessor, so every criterion is assessed at least once by a method that fits it, such as a work sample for a skill or a behaviour question for how someone has handled a situation, and every candidate goes through the same stages, with panel make-up, timings and dates. Its check job flags criteria nobody assesses, methods that don't fit the criterion, stages some candidates skip, and unstructured chats such as a culture fit interview. Use when a talent acquisition partner, recruiter, HR adviser or hiring manager asks for an interview plan, a selection plan, an assessment matrix, an interview process design, who should interview for what, how many interview stages to run, or wants an interview process checked before candidates are invited.
---

# Interview Plan

Produces the plan for one vacancy's interviews: every criterion against every stage, with the method and the assessor, plus the panel, timings and dates. Or checks a plan someone already has. Each criterion is tested properly, at the stage best placed to see it, and every candidate goes through the same process.

## When to use

- "Who should interview for what on the developer roles?"
- "Design a two-stage process for thirty customer adviser roles."
- "We've got a take-home, a technical interview and a final. Is anything tested twice or not at all?"
- "Check this interview process before we invite anyone."
- "Does the hiring manager need to be at every stage?"

Wrong tool for writing the questions (Structured Interview Guide), the task itself (Work Sample Task) or the rating scales (Scoring Guide), and for anything about a particular candidate.

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the criteria, from a role success profile or person specification. [none yet: offer Role Success Profile first]
2. **Essential:** the stages you have in mind, or the limits: how many stages, in person or video, how much of the candidate's time. [two stages: a 30-minute video interview, then a 60-minute interview with a work sample]
3. Who can assess: the hiring manager, TA, peers or others, and when they're free. [hiring manager and TA partner at each interview, a peer at the work sample]
4. Volume and dates: how many roles, expected candidates at each stage, closing date, target start. [placeholders]
5. Any fixed parts: an online test, a safety assessment, a take-home, vetting. [none]

Never ask about any candidate, and never ask for health details or protected characteristics. The plan is the same for everyone, so it needs nobody's details.

## Steps

Numbers in square brackets in these steps and the Quality checks are defaults. Use the user's own figure if they give one; otherwise use the default without asking.

1. Read what the user has given, including attachments. If they've given an existing plan, process or assessment matrix, this is a check job: run the Quality checks on it, list every problem with where it sits and why it matters, then write a corrected plan.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If the user says "just draft it", use the defaults and list them as assumptions.
3. Put the criteria down the side and the stages across the top. For each criterion, choose the method that fits what it is:
   - **A skill the job uses** (writing code, building a forecast, handling a call, fitting a meter): a work sample or practical task that copies the real work.
   - **How someone has handled situations before**: a behaviour question answered with STAR (situation, task, action, result).
   - **Judgement in situations a candidate may not have met yet**, including for people new to the work: a situational question built on a real dilemma from the job.
   - **A credential, licence or right to work**: a document check, outside the scored interview.
4. Place each criterion at the stage best placed to see it, and test it properly there. Every criterion appears at least once. Repeat a criterion at a later stage only when a second method adds evidence (a take-home, then a live session extending it), and say why. A stage that tests no criterion, such as a general chat or a "culture fit" conversation, is either tied to a criterion or cut: unstructured talk lets first impressions crowd out evidence. A practical call about notice, pay and working pattern can stay if it's labelled unscored.
5. Build in structure. Structured interviews came out as the top-ranked selection method in Sackett, Zhang, Berry and Lievens's 2022 re-analysis, and Campion, Palmer and Campion (1997) set out the components of structure: the same questions for every candidate, limited prompting, each answer rated against an anchored scale, notes taken, more than one interviewer, no discussion of candidates between interviews, and trained interviewers. In this plan that means the same questions in the same order at each stage, at least two assessors at every interview, each scoring alone before any discussion, and a briefing for every interviewer before the first candidate.
6. Make it the same for every candidate. Internal and external candidates, referrals and agency candidates go through the same stages, methods and criteria. Nobody skips a stage for a strong CV, a referral, a portfolio or the hiring manager's knowledge of them. Anyone who knows a candidate declares it, and a second assessor rates that candidate too. Reasonable adjustments change how a stage runs for a disabled candidate (more time, another format, questions in advance) while the criteria stay the same.
7. Set the panel and timings for each stage. Mix roles on a panel (the hiring manager, a peer, TA) so more than one view of the work is in the room, and name who leads and who takes notes. Allow [10] minutes for the candidate's questions and [15] minutes after each interview for every assessor to score alone, and keep to [five] interviews a day for any one assessor.
8. Add the dates and the candidate-facing parts: closing date, the dates of each stage, when candidates hear back [within three working days of each stage], how they ask for adjustments, whether questions or themes go to every candidate in advance (Advance Questions Sheet), and, for any take-home, what help including AI is allowed (Candidate AI Use Statement). Put right to work checks at the end, done the same way for every candidate under Home Office guidance.
9. Note the records: who keeps notes and scores, where, and for how long [six months after the decision, or your policy's period].
10. Run the Quality checks below and fix what fails before showing anything.
11. Present the plan, then **Assumptions** and **Check before you use it**: the assessors' diaries, the dates, the total time asked of candidates, your retention period, and that every interviewer has been briefed.
12. Offer a .docx, Structured Interview Guide or Work Sample Task for the stages, Scoring Guide for the anchored scales, or Interviewer Briefing for the panel.

## Output format

**Interview plan: [job title], [number] roles**
Criteria from [role success profile, date]. Plan owner: [TA role].

1. **Assessment matrix**

| Criterion | [Stage 1: format] | [Stage 2: format] | [Stage 3: format] |
| --- | --- | --- | --- |
| [criterion] | [method, assessor roles] | [blank, or method and reason for the repeat] | |

2. **Stages**

| Stage | Format and length | Panel (roles): lead, notes | Who takes part | Dates |
| --- | --- | --- | --- | --- |
| [stage] | [format, minutes] | [roles] | [every candidate who passes the stage before] | [dates] |

3. **Running order for one interview**: welcome and format [minutes], questions by criterion [minutes each], candidate's questions [minutes], assessors score alone [minutes].
4. **For candidates**: invitations by [date]; adjustments through [contact role]; questions in advance [yes or no, sent to everyone]; outcome within [number] working days; AI use statement [for any take-home].
5. **Checks outside the interview**: [right to work, qualifications, references], with when each happens.
6. **Records**: where notes and scores are kept, who can see them, and for how long.

The matrix and stages fit on one page.

## Try it

`examples/brackenholt-software-developer-interview-plan.md` is an engineering manager's draft interview plan for two remote Software Developer roles at Brackenholt Energy, a fictional 900-person energy supplier, with problems planted in it. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before writing the corrected plan. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-hiring-interviews), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- Every criterion is assessed at least once, and every scored stage assesses at least one criterion.
- Every skill the job uses is assessed by a work sample or practical task; no skill is assessed only by asking the candidate about it.
- Any criterion assessed at more than one stage has a stated reason the second method adds evidence.
- Every candidate goes through the same stages, methods and criteria; nobody skips a stage, and adjustments change the format only.
- No stage is an unstructured chat, and no cell says "culture fit", "gut feel" or "general chat".
- Every interview stage has at least two assessors by role, a named lead and note-taker, and time for each assessor to score alone before any discussion.
- Every stage has a length and a date or a marked placeholder, and the plan says when candidates hear back.

## Guardrails

- The one rule for this pack: "Claude drafts the questions, guides and letters. Interviewers gather the evidence, and people make every hiring decision." The plan says who gathers which evidence, when and how. Claude never scores, ranks or shortlists candidates; if candidates come up in the conversation, refer to them as Candidate A, B and C, and leave every decision to the panel.
- Personal data: interview notes and scores are personal data under UK GDPR and the Data Protection Act 2018. Candidates can ask for them through a subject access request, which has a one-month deadline, so write notes you'd be content for the candidate to read. Keep them only as long as the ICO's guidance on recruitment records and your policy allow, and keep candidates' details out of Claude. Follow your organisation's AI policy.
- Fairness: the same stages, methods and criteria for everyone. Never infer or mention protected characteristics. Make reasonable adjustments under section 20 of the Equality Act 2010, and keep pre-offer health questions within section 60. If any stage uses an AI tool to assess candidates, people still make the decision: check the tool against DSIT's Responsible AI in Recruitment guide and the UK GDPR rules on automated decision-making, and run a data protection impact assessment.
- Law: this draws on the Equality Act 2010 and the EHRC Employment Statutory Code of Practice (England, Scotland and Wales; Northern Ireland has its own equality law), UK GDPR, the Data Protection Act 2018 and ICO guidance, and the Home Office guidance on right to work checks. Check the current versions on legislation.gov.uk, ico.org.uk and GOV.UK. This is a draft, never legal advice.
- No invented facts: dates, panel members, timings and retention periods come from the user or stay as placeholders.
