---
name: interviewer-practice-session
description: Drafts the plan for a 60-minute practice session where hiring managers practise a structured interview before they run one, asking the guide's questions as written, probing for evidence with STAR, taking notes, scoring fictional candidate answers alone against the scoring guide, then comparing scores to calibrate. Includes the timed plan, role cards, fictional answers written to different anchors, a session lead's key, a quick round on questions never to ask, and the invitation. Use when a talent acquisition partner, recruiter or HR adviser asks for interviewer training, an interview skills session, hiring manager interview training, a calibration session, a scoring practice exercise, a practice interview workshop, or a way to get managers interviewing and scoring consistently.
---

# Interviewer Practice Session

Produces the plan for a 60-minute session where hiring managers practise the parts of a structured interview that most often go wrong: asking the same question the same way, probing for evidence, and scoring alone against anchors before comparing. Everyone scores the same fictional answers, so no real candidate's data comes near the room, and the spread of scores shows which anchors the panel reads differently.

## When to use

- "Our contact centre managers need interview training before the next hiring round. I've got an hour."
- "Design a calibration session so our panels score the same way."
- "Help me run a workshop on probing and STAR for new hiring managers."
- "Here are my notes for a practice session next week. Turn them into a plan."

This skill drafts only. Bring notes, an email thread or last year's session outline, and Claude lists what in them would undermine the practice or put candidates' data at risk, then drafts from them. Wrong tool for the briefing on interview day (use the Interviewer Briefing) or for writing the anchors (use the Scoring Guide). It's practice: nobody passes or fails, and it plays no part in deciding who may interview.

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the role attendees will interview for, with its interview guide and scoring guide if they exist. [one role; if there's no guide, Claude writes two practice questions with anchors and marks them as proposed]
2. **Essential:** who's attending: roles, how many and how much interviewing they've done. [6 to 12 hiring managers, mixed experience]
3. Format. [in person in one room; on Teams, use breakout rooms for the threes]
4. Who runs it. [a TA partner]
5. Length. [60 minutes]

Never ask for real candidates' answers, recordings, notes or scores. The session uses fictional answers Claude writes. If the user offers real material, leave it out, say why, and write fictional answers in its place.

## Steps

Numbers in square brackets in these steps and the Quality checks are defaults. Use the user's own figure if they give one; otherwise use the default without asking.

1. Read what the user has given: notes, an email, an earlier session plan, the interview guide or the scoring guide. This skill drafts only, so treat any of these as input: list every problem the Quality checks would catch in them, quoting where each sits and saying why it matters, then draft the session with each problem fixed or left as a visible placeholder.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If the user says "just draft it", use the defaults and list them as assumptions.
3. Pick [one or two] criteria from the scoring guide to practise: the ones panels are most likely to score differently, usually a people or judgement criterion. Take their questions and probes from the interview guide word for word.
4. Write the fictional answers. For each practice question, write three answers of 150 words or fewer in a spoken style, from Candidate A, B and C, each written to a different anchor without saying which. Make style and substance pull apart: one fluent and confident but thin on the candidate's own actions, one hesitant with specific actions and a clear result, one full of "we" that leaves the candidate's part unclear. Keep every answer free of names, protected characteristics and details of real people.
5. Write two or three role cards for the asking-and-probing round: a short fictional situation the "candidate" in each three answers from, with gaps the probes should uncover.
6. Plan the [60] minutes:
   - **Why structure** [5 min]: structured interviews came out as the top-ranked selection method in Sackett, Zhang, Berry and Lievens (2022). Name the parts of structure from Campion, Palmer and Campion (1997) that the session practises: the same questions for everyone, limited prompting, notes, anchored scales, scoring alone with no discussion between interviews.
   - **Asking and probing** [15 min], in threes: one asks the question as written, one answers from a role card, one watches with a checklist (asked as written, open probes such as "What did you do next?" and "What happened as a result?", no leading or closed probes, no new questions on a hunch). Rotate once.
   - **Notes** [5 min]: write what was said and done, the candidate's own words where possible, "I" or "we"; never appearance, accent, health or any protected characteristic, and no opinions.
   - **Score alone, then compare** [25 min]: the session lead reads Candidate A, B and C aloud for one practice question (a second question's answers are spare, for a follow-up). Everyone notes, then scores alone in writing against the anchors with one line of evidence. All scores are shown at the same moment (cards held up, or typed into the Teams chat on a count of three) before anyone speaks. Where scores spread by more than [one] point, ask the highest and lowest scorers which words in the answer they scored and which anchor they read them against. Agree what the anchor means; note any anchor that needs rewriting.
   - **Would you ask this?** [7 min]: quick cards covering pre-offer health and sickness questions (Equality Act 2010, section 60), age, childcare, where someone is "from", a fair question about a shift requirement, and what to do when a candidate asks for an adjustment or volunteers personal information.
   - **Close** [3 min]: each attendee writes one thing they'll do in their next interview.
   Check the times add up to the session length; if it's shorter, cut the probing round before the scoring round.
7. Write the session lead's notes: the anchor each fictional answer was written to and why, prompts for the comparison, and a reply to "I can tell in the first five minutes" (first impressions pick up style, and the anchors ask for evidence).
8. Write a pre-session note to attendees: what the session is, that it's practice, what to bring, and a line asking whether anything would make it easier to take part (materials in advance, captions, a quiet room), handled through [the organisation's process].
9. Record only an anonymous spread of scores for each answer, to show which anchors need work. Nothing about any attendee's performance is recorded or reported by name.
10. Run the Quality checks below and fix what fails before showing anything.
11. Present the plan, then **Assumptions** and **Check before you use it**: the date, room and format, that the practice questions and anchors match the live guides, and who will rewrite any anchor the session shows is unclear.
12. Offer a .docx, a slide outline, printable role cards and score cards, the Scoring Guide to rewrite anchors where scores spread, or the Interviewer Briefing for the first real interviews.

## Output format

**Interviewer practice session: [role], [date]**
For [attendee roles and number]. Run by [role]. [60] minutes, [format].

1. **Plan**

   | Time | Section | What happens | Materials |
   | --- | --- | --- | --- |

2. **Practice questions**: the question, probes and anchors, from the live guides.
3. **Role cards**: two or three, one short paragraph each.
4. **Fictional answers**: Candidate A, B and C for each practice question, no level shown.
5. **Session lead's notes**: the anchor each answer was written to and why; comparison prompts; replies to common pushback.
6. **Would you ask this?** cards: [eight] questions, each with the answer and the reason.
7. **Pre-session note** to attendees, under 120 words.
8. **After the session**: score spread for each answer, no names, and the anchors to rewrite.

Plan on one page; the handouts follow it.

## Try it

`examples/brackenholt-customer-adviser-practice-notes.md` holds a talent acquisition partner's rough notes for a practice session before the Customer Adviser intake at Brackenholt Energy, a fictional 900-person energy supplier, with problems planted in them. When the user says "try it", "show me" or "use the example", read that file, list every problem you find in the notes with where it sits and why it matters, then draft the session from them with each problem fixed or left as a visible placeholder. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-hiring-interviews), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- The plan adds up to the session length, and at least [20] minutes go on scoring fictional answers alone and comparing.
- Every candidate answer and role card is fictional and written for the session; no real candidate's words, recording, notes or scores are used.
- Each attendee scores alone, in writing, against the scoring guide, and all scores are shown at once before anyone discusses them.
- The fictional answers include one that sounds polished but is thin on evidence and one that is hesitant but full of evidence, and the session lead's notes say which anchor each was written to.
- The practice criteria are job behaviours from the scoring guide; nothing in the session teaches culture fit, gut feel, first impressions or "reading people" as a basis for scoring.
- The session covers questions never to ask, including pre-offer health questions, and what to do with an adjustment request.
- Nothing records or reports an attendee's scores or performance by name.

## Guardrails

- The one rule for this pack: Claude drafts the questions, guides and letters. Interviewers gather the evidence, and people make every hiring decision. Claude writes the plan and the fictional answers; the attendees do the asking, probing and scoring, and the session judges no one.
- Real candidates' answers, recordings and scores are personal data under UK GDPR and the Data Protection Act 2018, collected for that recruitment; using them to train interviewers is a new purpose the candidate was never told about. Use fictional material only, keep attendees' practice scores anonymous, and follow the ICO's guidance and your organisation's AI policy.
- Practise one standard for every candidate. Never infer or mention protected characteristics in the fictional answers or role cards. Teaching gut feel or first impressions invites the bias the Equality Act 2010 guards against, direct and indirect. Ask attendees about reasonable adjustments for taking part, as you would for candidates (section 20).
- The "Would you ask this?" round reflects the Equality Act 2010, including section 60 on pre-offer health questions, and the EHRC Employment Code. Check the current versions and your own policy. This is a draft session plan, never legal advice.
- Dates, rooms, attendee numbers and guide content come from the user or stay as placeholders.
