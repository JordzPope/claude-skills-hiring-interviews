---
name: scoring-guide
description: Drafts or checks a scoring guide for a structured interview, with a behaviourally anchored rating scale for each criterion that describes what a weak, sound and strong answer contains, on the organisation's scale (1 to 5 by default), a list of what does not count as evidence, and the rule that each interviewer scores alone before any discussion. The check job flags vague anchors such as "good" or "excellent", anchors that reward confidence or polish over substance, culture fit used as a criterion, and criteria left without a scale. Use when a talent acquisition partner, recruiter, HR adviser or hiring manager asks for an interview scoring guide, a rating guide, interview marking criteria, a scoring rubric, behaviourally anchored rating scales (BARS), what a good answer looks like for each question, model answers for an interview, or to check a scoring guide before interviews start.
---

# Scoring Guide

Produces the guide a panel scores from: for each criterion, what a weak, sound and strong answer contains, written as things an interviewer can hear in the answer, plus what doesn't count as evidence. Or checks a guide someone already has. Written before the first interview, it gives every interviewer the same standard, so a 3 means the same thing for every candidate and every panel member.

Anchored rating scales and rating each answer on its own are two of the evaluation components of interview structure in Campion, Palmer and Campion (1997). Structured interviews came out as the top-ranked selection method in Sackett, Zhang, Berry and Lievens (2022). This skill writes the scales; interviewers do the scoring.

## When to use

- "Write a scoring guide for our team leader interview questions."
- "What does a 1, a 3 and a 5 look like for 'coaching others'?"
- "Our hiring managers score on gut feel. I need anchors they can actually use."
- "Check this rating guide before the panel uses it on Thursday."
- "Turn our Success Profiles behaviours into a marking guide for the interview."

Wrong tool for scoring, ranking or shortlisting real candidates: interviewers score from their own notes, and the panel decides at the debrief (see the Debrief Agenda skill). To agree the criteria first, use the Role Success Profile; to write the questions, use the Structured Interview Guide; for the sheet interviewers write on, use the Interviewer Note Sheet.

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the role, the interview stage and the criteria assessed at it, with a line on what each means in this job. [four to six criteria; if only a job description is given, Claude proposes criteria from it and marks them as proposed]
2. **Essential:** the questions and probes for each criterion. [if there are none yet, Claude writes anchors to the criterion and the user maps questions to them later]
3. The rating scale. [1 to 5, with anchors written at 1, 3 and 5, and 2 and 4 between them. Public-sector users on the Civil Service Success Profiles: the scale their organisation sets, often 1 to 7]
4. The level of the role, and what the person must bring on day one compared with what they'll learn in the job. [the level advertised; nothing taught in induction is required]
5. Any minimum score for an essential criterion. [none; if the panel wants one, it agrees it before the first interview]

Never ask for candidates' names, CVs, answers, notes or scores, or for health details or protected characteristics. The guide describes answers. If the user pastes a real candidate's answer and asks for a score, say that interviewers do the scoring, and offer to sharpen the anchors so the panel can score it consistently.

## Steps

Numbers in square brackets in these steps and the Quality checks are defaults. Use the user's own figure if they give one; otherwise use the default without asking.

1. Read what the user has given, including any attached interview guide, success profile or job description. If they've given an existing scoring guide, rating scale or scorecard, this is a check job: run the Quality checks on it, list every problem with where it sits and why it matters, then write a corrected guide.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If the user says "just draft it", use the defaults and list them as assumptions.
3. Check the criteria. Each one must be a skill, behaviour or piece of knowledge the job needs, tied to real work in the role. Where a criterion is "culture fit", "attitude", "presence" or a personality trait, rewrite it as the behaviour the hiring manager means ("works with other teams to fix a customer's problem"), mark it as proposed and say what you changed. List any criterion with no scale and any question with no criterion.
4. Write the anchors for each criterion at [1, 3 and 5] as a behaviourally anchored rating scale. Each anchor lists two to four things the answer contains, following the parts of a STAR answer:
   - the situation and task, and whether it's a real example from the candidate's own experience;
   - the actions they took themselves ("I" rather than "we") and the reasons they give;
   - the result, how they knew, and what they'd do differently.
   For a situational question, anchor on what they'd do, in what order and why. For a work sample, anchor on the steps taken and the standard of the finished work.
5. Make the levels differ by content. A strong answer has a specific example, the candidate's own actions with reasons, a result they can point to, and holds up under the probes. A sound answer has a real example and clear actions, with gaps in the reasoning or the result. A weak answer has no example, a general statement of what people should do, only what others did, or an approach that would cause harm in this job. Write the specific version of each for this criterion and role.
6. Test every anchor: would two interviewers who heard the same answer place it at the same level? Replace each evaluative word ("good", "excellent", "strong", "poor", "impressive") with what the answer contains. Remove anything that rewards delivery or background: confidence, fluency, polish, speed, eye contact, accent, the organisation's own jargon, insider knowledge only an internal candidate could have, or a shared employer, school or sector.
7. Pitch the strong anchor at the level of the role. Allow examples from paid work, volunteering, education or caring wherever the criterion permits, so people new to the sector or to work can reach every level.
8. Write **What doesn't count as evidence** for the whole guide: confidence, polish, nerves, accent, appearance, how long someone talks, shared background or interests, knowing someone at the organisation, anything about a protected characteristic, and use of an agreed adjustment (questions in advance, notes, extra time), which never lowers a score.
9. Write **How to score**, following Campion's evaluation components: score each answer against the anchors from your notes, straight after the interview; score alone, before any discussion with the panel; write one line of evidence for every score; use 2 or 4 when an answer sits between anchors; don't discuss candidates between interviews; bring scores to the debrief, where they're shared before anyone talks. State any minimum score and who agreed it.
10. Run the Quality checks below and fix what fails before showing anything.
11. Present the guide, then **Assumptions** and **Check before you use it**: that each criterion matches the agreed success profile, that the strong anchor fits the level of the role, any minimum scores, and that every panel member has the guide before the first interview.
12. Offer a .docx, a one-page copy for each interviewer, the Interviewer Note Sheet built on the same questions, or the Interviewer Practice Session to calibrate the panel on these anchors.

## Output format

**Scoring guide: [role], [interview stage]**
Scale: [1 to 5]. Anchors at [1, 3 and 5]; [2 and 4] sit between. Agreed by [hiring manager role] on [date].

1. **How to score**: the rules from step 9, six lines at most.
2. **Criteria**: one block per criterion, in the order the interview guide asks them.

   **[Criterion]**: [what it means in this job]. Questions: [question numbers].

   | Score | The answer contains |
   | --- | --- |
   | 5 Strong | [two to four points an interviewer can hear] |
   | 4 | Some of 5, more than 3. |
   | 3 Sound | [two to four points an interviewer can hear] |
   | 2 | Some of 3, more than 1. |
   | 1 Weak | [two to four points an interviewer can hear] |

   Minimum score: [none, or the agreed figure].
3. **What doesn't count as evidence**: one short list for the whole guide.
4. **What changed** (check job only): each change and why, one line each.

About one page for every two criteria.

## Try it

`examples/brackenholt-team-leader-scoring-guide.md` is a scoring guide drafted for the Team Leader, Customer Operations vacancy at Brackenholt Energy, a fictional 900-person energy supplier, where internal and external candidates sit the same interview. Problems are planted in it. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before writing the corrected guide. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-hiring-interviews), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- Every criterion assessed at this stage has its own anchors at [1, 3 and 5], every question maps to a criterion, and no criterion is left without a scale.
- Every anchor names content an interviewer can hear in an answer (an example, an action, a reason, a result); none rests on an evaluative word such as "good", "excellent", "strong" or "poor".
- No anchor rewards delivery or background: confidence, fluency, polish, presence, speed, insider knowledge, or a shared employer, school or sector.
- No criterion is "culture fit", "attitude" or a personality trait; each is a skill, behaviour or piece of knowledge the job needs.
- With the level labels covered, a reader can still tell a 3 from a 5 by what the answer contains.
- The guide tells each interviewer to score every answer alone, from their notes, before any discussion, and lists what doesn't count as evidence.
- Nothing in the guide scores, ranks or comments on a real candidate.

## Guardrails

- The one rule for this pack: Claude drafts the questions, guides and letters. Interviewers gather the evidence, and people make every hiring decision. Claude writes what answers at each level contain and never rates a real candidate's answer. Each interviewer scores from their own notes, and the panel decides.
- Work with roles and criteria only. Keep candidates' names, answers and scores out of Claude, and follow your organisation's AI policy. Scores and the notes behind them are personal data under UK GDPR and the Data Protection Act 2018, and a candidate can request them, so write anchors you'd be content for a candidate to read.
- Use one guide for every candidate at the stage, internal and external alike. Never infer or mention protected characteristics. A criterion or anchor that puts people who share a protected characteristic at a disadvantage without a job reason risks indirect discrimination under the Equality Act 2010, so give each one a job reason. An agreed reasonable adjustment (section 20) never counts against a score. Positive action under sections 158 and 159 is a narrow, separate step that people take under your policy; never build it into the anchors.
- This follows the Equality Act 2010 and the EHRC Employment Code. Check the current versions on legislation.gov.uk and the EHRC website, and your own policy. This is a draft guide, never legal advice.
- Criteria, the scale, minimum scores and role details come from the user or stay as placeholders.
