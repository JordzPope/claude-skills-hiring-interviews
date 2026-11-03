---
name: candidate-feedback-note
description: Drafts or checks written feedback for a candidate after a hiring interview, written only from the panel's own notes, scores and recorded decision, with what went well against each criterion, one or two specific things that would have strengthened the application, and the decision stated plainly, under UK practice. Use when a talent acquisition partner, recruiter, HR adviser or hiring manager asks for interview feedback, feedback for an unsuccessful candidate, feedback after a final interview, feedback for an internal candidate who didn't get the job, a rejection email with feedback, talking points for a feedback call, or a check of feedback before it goes to the candidate.
---

# Candidate Feedback Note

Turns the panel's evidence and decision into feedback a candidate can use: what they did well, criterion by criterion, one or two specific things that would have made the application stronger, and the decision in plain words. Or checks feedback a hiring manager has drafted against the panel's notes before it goes out. It turns notes that say "good vibes" into feedback you'd be happy for the candidate to read beside their own interview record.

## When to use

- "Candidate B has asked for feedback after the final interview. Here's the decision record, can you write it?"
- "The hiring manager has drafted feedback for an internal candidate. Check it before I send it."
- "I need feedback for someone who didn't get past the first interview, from these scores."
- "What can I say to a candidate who asked why they didn't get the job?"
- "Turn the debrief notes into talking points for a feedback call."

Wrong tool for the decision itself, which belongs to the panel (use Decision Record to write it down first), or for the short message to candidates who haven't asked for feedback (use Not Progressing Email).

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the panel's evidence and decision for this one candidate: the decision record or debrief notes, with each criterion assessed at this stage, the agreed score and the evidence notes (what the candidate said or did). Claude never supplies these.
2. **Essential:** the stage and the decision. [final interview; not offered the role]
3. Internal or external candidate. [external]
4. Your scoring guide, so "what a stronger answer would show" matches it. [read from the notes; otherwise described in plain words, with no scores quoted]
5. Your policy on feedback and on keeping details for future roles. [written feedback on request, and a call if the candidate wants one; no talent pool]
6. Who sends it, and how the candidate asked. [the talent acquisition partner, replying by email to the candidate's request]

Never ask for other candidates' notes or scores, the successful candidate's evidence, health information, adjustment details or protected characteristics. If the user pastes them, leave them out of the feedback and say so. Refer to the candidate by letter; their first name goes into the greeting as a placeholder.

## Steps

Numbers in square brackets in these steps and the Quality checks are defaults. Use the user's own figure if they give one; otherwise use the default without asking.

1. Read what the user has given, including attachments. If they've given drafted feedback, this is a check job: compare it line by line with the panel's notes, run the Quality checks, list each problem with the line it sits in and why it matters, then write corrected feedback. If there are no panel notes, check everything else and say you can't confirm the feedback matches the evidence until you see them.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If the user says "just draft it", draft with visible gaps and list the assumptions.
3. Check the evidence exists before writing a word. For each criterion assessed at this stage, find the agreed score and at least one evidence note. Where either is missing, write `[Panel's evidence on this criterion: not yet provided]` and tell the user. Never infer a score, rate an answer yourself or fill a gap from the CV, the job description or what seems likely. If the user asks how well the candidate did, say that's the panel's judgement and point to the notes.
4. Pick what went well. For each criterion the panel recorded as a strength, take one specific thing the candidate said or did ("your example of coaching a new adviser on call wrap-up, and the drop in wrap time you measured"). Two or three strengths are enough.
5. Pick what would have strengthened the application: the one or two criteria the decision turned on, as the record states them. For each, say what a stronger answer would have shown, using the scoring guide's description of a sound or strong answer. Where the notes show a STAR answer missing a part (the situation, the task, the action or the result), name the missing part. Stop at two points, even if the notes hold more.
6. State the decision plainly in the first two sentences: "We've decided not to offer you the role." Give no reason beyond the criteria in the record.
7. Take out every comparison with other candidates, including the successful one: "a very strong field", "the successful candidate had more experience", "it was close". Measure this candidate against the criteria and nothing else.
8. Take out anything that touches a protected characteristic or a proxy for one: age-coded words ("energetic", "overqualified", "recent graduate"), accent or "native speaker", family or caring commitments, gaps in work history, health, and any adjustment the candidate had. Replace "culture fit" and other unexplained "fit" language with the criterion it stood for. If no criterion sits behind it, cut it and tell the user, because the decision itself may need a second look.
9. Run the subject access test. The candidate can ask for their interview notes and scores under UK GDPR, and the organisation has one month to respond. Read every line against the notes: a line that is warmer, harsher or different in substance from the record (a strength the panel scored low, a reason the record doesn't give, the real reason left out) gets rewritten to match it.
10. Handle future roles. Make no promise or hint ("you'll walk into the next one", "we'll be in touch when something comes up"). If policy allows, add a general line that the candidate is welcome to apply again. Keeping their details for future vacancies needs their agreement: say what will be kept, for how long, for what kind of role, and how to say no. For an internal candidate, offer a development conversation with their own manager, and ask before sharing any of the feedback with that manager.
11. Write it kindly and directly, one person to another: their first name once, "we" for the panel, plain English, no internal codes or score numbers unless your policy shares them. Keep it to [400] words at most.
12. Build the evidence trail: each line of the feedback against the criterion and the note it came from. It goes on the recruitment record with the feedback and is never sent.
13. Run the Quality checks below and fix what fails before showing anything.
14. Present the feedback and the evidence trail, then a short **Assumptions** list and a **Check before you use it** list: that the panel chair has read and agrees every line, that the notes you worked from are the ones held in the ATS, your policy on sharing scores and on future roles, and that nothing refers to an adjustment.
15. Offer a .docx, talking points for a feedback call (the same content, so the call and the note match), or the Decision Record skill if the panel's reasons aren't written down yet.

## Output format

**Subject:** Your interview for [role]: feedback

Dear [first name],

[One line of thanks for something specific, such as their time or their preparation for the task. Then the decision, plainly, in the next sentence.]

[One sentence on what the panel assessed at this stage: the criteria, in plain words.]

**What went well**
- **[Criterion]:** [the specific thing they said or did, from the notes]
- [two or three in all]

**What would have strengthened your application**
- **[Criterion the decision turned on]:** [what a stronger answer would have shown, from the scoring guide]
- [one or two in all]

[Next steps: how to ask for a call, by when and with whom. A future-roles line only if policy allows, with the consent wording if details will be kept.]

[Sender's name and role]

**Evidence trail (kept on the recruitment record, never sent)**

| Line in the feedback | Criterion | Panel note or score it comes from |
| --- | --- | --- |

[400] words at most for the note. On a check job, the list of problems comes first.

## Try it

`examples/brackenholt-team-leader-feedback.md` holds the panel's decision record for an internal candidate for the Team Leader, Customer Operations role at Brackenholt Energy, a fictional 900-person energy supplier, and the feedback the hiring manager drafted from it, with problems planted in the draft. When the user says "try it", "show me" or "use the example", read that file, run the check job on the draft against the panel's record and list every problem you find before rewriting it. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-hiring-interviews), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- The decision appears in the first two sentences, in plain words, and matches the recorded decision.
- Every strength and every development point names a criterion and traces to a note or score in the panel's record. Nothing contradicts the record: a criterion the panel scored below its threshold never appears as a strength, and the criteria the decision turned on are the ones named.
- There are at most two development points, and each says what a stronger answer would have shown. No vague lines such as "not quite the right fit", "just missed out" or "lacked presence", and no "culture fit".
- No comparison with other candidates or with the successful candidate, including "a strong field" and "it was close".
- Nothing mentions or hints at a protected characteristic, health, an adjustment, family or caring commitments or gaps in work history, and there are no age-coded words or comments on accent.
- No promise or hint about future roles. Keeping details for future vacancies appears only with the candidate's agreement, the period and how to say no.
- The note is [400] words at most, uses the candidate's first name once, and names no other candidate or panel member.

## Guardrails

- The one rule for this pack: Claude drafts the questions, guides and letters. Interviewers gather the evidence, and people make every hiring decision. The panel has made this decision on its own evidence, and this note reports both without adding to them. Claude never scores, re-judges or ranks the candidate, never writes evidence the notes don't hold, and leaves a gap wherever the record is silent.
- Personal data: interview notes and scores are personal data under UK GDPR and the Data Protection Act 2018, and the candidate can request them through a subject access request. Paste only this candidate's notes, with their name replaced by a letter, and never another candidate's. Follow your organisation's AI policy. Keep the feedback with the recruitment record for your retention period: the ICO's guidance says unsuccessful candidates' records shouldn't be kept beyond the period in which a claim could be brought without a clear business reason, and six months is common practice.
- Fairness: give every candidate, internal or external, the same standard of feedback against the same criteria. Never infer or mention a protected characteristic. A reason in feedback that links to one is evidence in a claim of direct or indirect discrimination under the Equality Act 2010, and a reasonable adjustment under section 20 is never a weakness. If a reason sits outside the criteria, flag it so a person reviews the decision.
- Law: this follows the Equality Act 2010, the EHRC Employment Statutory Code of Practice, UK GDPR, the Data Protection Act 2018 and ICO guidance on recruitment records. Check the current versions and your own policy. This is a draft, never legal advice; take advice before replying if the candidate has raised a complaint or a discrimination concern.
- No invented facts: evidence, scores, the decision and any policy wording come from the user or stay as placeholders.
