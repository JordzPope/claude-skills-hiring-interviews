---
name: interviewer-note-sheet
description: Drafts or checks an interviewer note sheet for a structured interview, with each question and its probes in order, space to record what the candidate said and did, a score box for each criterion filled in alone after the interview against the scoring guide, and a reminder that interview notes are personal data a candidate can request. The check job flags opinion boxes such as overall impression or gut feel, culture fit, comments on appearance or accent, and anything about health or protected characteristics. Use when a talent acquisition partner, recruiter, HR adviser or hiring manager asks for an interview notes template, an interviewer note sheet, an interview record form, an interview evidence form, an interview scoresheet, a form for interviewers to write on, or to check the notes form a panel uses.
---

# Interviewer Note Sheet

Produces the sheet an interviewer writes on during one interview: each question in order, space for what the candidate said and did, and a score box filled in afterwards. Or checks a sheet already in use. It keeps the evidence apart from impressions, so scores rest on what was said and the notes hold up when a candidate asks to see them.

Taking notes and rating each answer from them are two of the evaluation components of interview structure in Campion, Palmer and Campion (1997). The sheet gives every interviewer the same place to put the evidence.

## When to use

- "I need a notes template for the smart-meter engineer interviews."
- "Our hiring managers write 'good vibes' on the form. Give me something that gets them writing down evidence."
- "Make an interview record form to go with this interview guide."
- "Check our interview notes form before the panel uses it."
- "What should interviewers write down, and what should they never write?"

Wrong tool for writing the questions (use the Structured Interview Guide) or the anchors interviewers score against (use the Scoring Guide). The sheet holds evidence; scores come from each interviewer and the decision from the panel at the debrief.

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the interview guide: the questions in order, the probes, and the criterion each question assesses. [if there's no guide, ask for one or suggest the Structured Interview Guide skill first]
2. **Essential:** the scoring scale and where the anchors are. [1 to 5, scored against the Scoring Guide for this role]
3. The format, and any practical task or work sample. [one-to-one or panel by video, questions only]
4. Where notes go and by when. [uploaded to the applicant tracking system (ATS) within one working day; paper copies shredded once uploaded]
5. How long notes are kept. [your organisation's retention policy; six months after the decision for unsuccessful candidates is common practice]

Never ask for candidates' names, health details or protected characteristics. The sheet identifies the candidate by a letter or ATS reference. If the user's draft holds personal details, leave them out of the corrected sheet and say so.

## Steps

Numbers in square brackets in these steps and the Quality checks are defaults. Use the user's own figure if they give one; otherwise use the default without asking.

1. Read what the user has given, including any attached interview guide or scoring guide. If they've given an existing note sheet, interview form or scoresheet, this is a check job: run the Quality checks on it, list every problem with where it sits and why it matters, then write a corrected sheet.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If the user says "just draft it", use the defaults and list them as assumptions.
3. Write the header: role, stage, candidate reference (a letter or ATS reference), interviewer role, date, and **Adjustments in place**, written as what the interviewer does differently ("questions shared in advance; the candidate may use their notes"), with no reason or diagnosis.
4. Put the personal data reminder at the top, in a box: these notes are personal data under UK GDPR; the candidate can ask to see them through a subject access request, and they could be read at an employment tribunal; write only what you'd be content for the candidate to read.
5. Give each question its own block, in the guide's order: the question as written, its criterion, the probes with a tick box for each one asked, and a space headed **What they said and did**. Prompt that space with the parts of a STAR answer (situation and task, what they did themselves, the result) so the interviewer notes what's there and what's missing. For a situational question, use "What they'd do, and why". For a practical task, list the steps to watch in order, with space to note what the candidate did at each and any safety step missed.
6. Write **How to take notes** in five or six lines:
   - Write facts and the candidate's own words where you can. Note whether they said "I" or "we".
   - Note where an answer was a general statement with no example, or where a probe took it no further.
   - Write nothing about appearance, dress, accent, voice, age, health, family, nationality, religion or any other protected characteristic, and no opinions ("nervous", "nice", "not one of us").
   - If a candidate mentions a health condition or other personal detail, leave it off the sheet. If they ask for an adjustment, tell [the TA partner] straight after the interview.
7. Add the scoring section, kept apart from the notes: one row per criterion, a score box and a line headed **Evidence for this score** that points back to the notes. Say: fill this in alone, after the candidate has left, against the Scoring Guide, before any discussion with the panel.
8. Leave out any box for overall impression, gut feel, culture fit, first impressions, personality, "would you hire" or a recommendation. The panel decides at the debrief, criterion by criterion.
9. Add the footer: where the sheet goes and by when, who can see it, no copies on personal devices or in chat channels, and how long it's kept.
10. Run the Quality checks below and fix what fails before showing anything.
11. Present the sheet, then **Assumptions** and **Check before you use it**: your retention period, where completed sheets are stored, whether your ATS has its own fields this should match, and that the scale matches the Scoring Guide.
12. Offer a .docx or a printable version with writing space, the Scoring Guide if the anchors aren't written yet, or the Interviewer Briefing for the panel.

## Output format

**Interview notes: [role], [stage]**
Candidate: [letter or ATS reference] · Interviewer: [role] · Date: [date]
Adjustments in place: [what the interviewer does, or "none"]

> **These notes are personal data.** The candidate can ask to see them. Write only what you'd be content for them to read: what they said and did.

**How to take notes**: the lines from step 6.

**Question [n]: [question as written]** · Criterion: [criterion]
Probes asked: ☐ [probe] ☐ [probe] ☐ [probe]
What they said and did:
- Situation and task:
- What they did themselves:
- Result:

(One block per question. For a practical task: **Step** | **What they did**.)

**Scores**: fill in alone, after the candidate has left, against the Scoring Guide.

| Criterion | Score [1 to 5] | Evidence for this score |
| --- | --- | --- |
| [criterion] | | |

**After the interview**: upload to [the ATS] within [one working day], then shred paper copies. Seen by [the panel and the TA team] only. Kept for [retention period].

About one printed page per question, with writing space.

## Try it

`examples/brackenholt-smart-meter-engineer-notes.md` is the note sheet field supervisors use for the Smart-Meter Engineer vacancy at Brackenholt Energy, a fictional 900-person energy supplier, where candidates have an interview and a practical assessment. Problems are planted in it. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before writing the corrected sheet. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-hiring-interviews), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- Every question in the guide appears in the same order, with its criterion and probes, and has its own space for what the candidate said and did.
- No box asks for an opinion or verdict: no "overall impression", "gut feel", "culture fit", "first impressions", "personality", "would you hire" or recommendation field.
- Nothing invites comments on appearance, dress, accent, voice, age, health, sickness absence, family or any other protected characteristic, and the note-taking lines say not to record them.
- The score boxes sit apart from the notes, are filled in alone after the interview against the Scoring Guide, and each has a line for evidence.
- The personal data reminder is at the top and says the candidate can request the notes; nothing on the sheet says the notes are private or kept from the candidate.
- The candidate appears as a letter or reference only, and the sheet says where it goes, by when, who sees it and how long it's kept.

## Guardrails

- The one rule for this pack: Claude drafts the questions, guides and letters. Interviewers gather the evidence, and people make every hiring decision. Claude drafts the sheet; interviewers write the notes and the scores, and the panel decides at the debrief. Claude never fills in notes or scores for a real candidate.
- Completed sheets are personal data under UK GDPR and the Data Protection Act 2018. A candidate can request them through a subject access request (one month to respond), and they're kept only as long as your retention policy allows, following the ICO's guidance on recruitment records. Keep completed sheets out of Claude and follow your organisation's AI policy.
- Use the same sheet for every candidate at the stage. Never infer or record protected characteristics. Comments on appearance, accent or "fit" carry bias and can become evidence in a discrimination claim under the Equality Act 2010. Section 60 restricts questions about health or disability before a job offer, so the sheet never asks interviewers to note them. Agreed reasonable adjustments (section 20) appear only as what the interviewer does.
- Check the current versions of the Equality Act 2010, the EHRC Employment Code and the ICO's guidance, and your own policy. This is a draft form, never legal advice.
- Retention periods, systems and deadlines come from the user or stay as placeholders.
