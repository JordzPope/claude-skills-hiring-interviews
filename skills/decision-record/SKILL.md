---
name: decision-record
description: Drafts or checks the record of a hiring decision a UK interview panel has already made about one candidate, setting out the decision, each criterion with the panel's scores and the evidence behind them, any adjustments made, who decided and when, and how long the record is kept, written so it is accurate and fair if the candidate reads it through a subject access request. Use when a talent acquisition partner, recruiter, HR adviser or hiring manager asks to write up an interview decision, record why a candidate was or wasn't appointed, turn debrief notes into a selection decision record, prepare a SAR-ready interview record, or check a decision record or interview write-up before it is filed or disclosed.
---

# Decision Record

Writes down a decision the panel has already made: the outcome, the evidence on each criterion, the adjustments made, and who decided and when. Or checks a record someone else wrote. The test throughout is whether you'd be comfortable if the candidate read it under a subject access request, because they can.

## When to use

- "The panel has decided not to appoint Candidate C. Write the decision record from our scores and notes."
- "Turn the debrief notes into a decision record for the file."
- "A candidate has made a subject access request. Check our interview write-up before we send it."
- "Check the hiring manager's decision record before it goes in the ATS."
- "What should a hiring decision record include?"

Wrong tool for making or suggesting the decision, which belongs to the panel; to run the meeting where it's made, use Debrief Agenda. To tell the candidate, use Candidate Feedback Note or Not Progressing Email.

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the panel's decision for this candidate, as made, and the date. Claude never supplies this.
2. **Essential:** the criteria, marked essential or desirable, the scoring guide, and each panel member's scores and evidence notes, or the debrief record.
3. Who decided, by role, and who chaired. [the panel, by role, chaired by the TA partner]
4. Adjustments offered and made during the process, described as what was done. [none requested]
5. Your retention period and where the record is kept. [held in the ATS, seen by the TA team and the panel; deleted six months after the candidate is told the outcome; for the person appointed, it moves to their personnel file]
6. Any decision rules agreed before interviews. [at least 3 out of 4 on every essential criterion]

Never ask for the candidate's name or contact details, the condition or reason behind an adjustment, protected characteristics, or anything found outside the process, such as social media. If the notes include them, leave them out and say so.

## Steps

1. Read what the user has given: scores, interview notes, the debrief record, any draft. If they've given an existing record, this is a check job: compare it line by line with the scores and notes, run the Quality checks, list every problem with where it sits and why it matters, then write a corrected record.
2. Ask for missing essentials once, in one message, five questions at most, with the defaults shown. If the user says "just draft it", draft with visible gaps for anything missing and list the assumptions.
3. Confirm the decision exists before writing anything else. If the panel hasn't decided, stop, say this record is written from the panel's decision, and offer the Debrief Agenda. If the user asks what the decision should be, say it's the panel's and list what their notes still need to show. Never infer a decision from the scores, and never suggest one.
4. Work criterion by criterion, in the scoring guide's order. For each, give the criterion, whether it's essential or desirable, each panel member's score and the agreed score (if the scores aren't given by role, show them as Panel member 1, 2 and 3 and list that under Check before you use it), the anchor it matches in the guide's behaviourally anchored rating scale, and the evidence: what the candidate said or did, paraphrased factually from the notes. Where a criterion has no score or evidence, write `[Panel's evidence on this criterion: not yet provided]`.
5. Sort every remark in the notes or the draft:
   - Evidence about a criterion: keep it, in neutral words.
   - Opinion with no evidence ("came across as arrogant", "not polished"): leave it out, and add a question for the panel under Check before you use it: what did the candidate say or do behind it?
   - Remarks unrelated to the criteria (commute, hobbies, the previous job holder, "culture fit"): leave them out and tell the user.
   - Anything touching a protected characteristic, health, family or a diagnosis: leave it out, tell the user plainly, and advise HR review, because it may suggest the decision took it into account.
6. Check the reasons match the scores. The reasons for the decision must follow from the scores and the decision rules agreed before interviews. If a reason rests on a criterion where the candidate scored well, or on a factor outside the guide, flag the mismatch and leave `[Panel to confirm the reason: it doesn't match the scores on this criterion]`. Never change a score or a reason to make them fit; that's for the panel.
7. Record adjustments as what was done (questions in advance, extra time, a break, camera off) and that the panel scored against the same guide. Leave out the reason and any condition.
8. Only if the panel used the positive action tie-break under section 159, record that it found the candidates as qualified as each other on the evidence, the basis for the organisation's reasonable view that the group is disadvantaged or under-represented, and that HR confirmed the conditions. Claude never adds this.
9. Complete the record details: who decided and when, who wrote the record and when, where it's kept, who can see it, and the deletion date worked out from the retention period.
10. Apply the subject access test to every sentence: factual, about the criteria, and something the panel would be comfortable for the candidate to read. Rewrite or flag any that fail. Use the same neutral tone whether or not the candidate was appointed.
11. Run the Quality checks and fix what fails before showing anything.
12. Present the record, then **Assumptions** and **Check before you use it**: that each panel member agrees the wording, that the scores match the ATS, the retention period and deletion date, and anything flagged for HR review.
13. Offer a .docx, or the Candidate Feedback Note skill, which works from the same evidence.

## Output format

**Hiring decision record: [role], [vacancy reference]**

Candidate: [letter or candidate reference]. Stage: [stage]. Interview date: [date]. Panel: [roles]. Scoring guide: [name and version], scale [scale].

**Decision**: [the panel's decision, as made]. Decided by: [roles]. Date: [date].

**Evidence by criterion**

| Criterion | Essential or desirable | Scores (by role) and agreed score | Anchor matched | Evidence: what the candidate said or did |
| --- | --- | --- | --- | --- |

**Reasons for the decision**: [two to four sentences, each naming the criteria and scores it rests on]

**Dissent**: [any panel member who disagreed, with their reason by criterion, or "none recorded"]

**Adjustments**: [what was offered and made, or "none requested"]

**Positive action**: [only if the panel used section 159; otherwise leave this line out]

**Record details**: written by [role] on [date]; agreed by [roles] on [date]; held in [system]; seen by [roles]; delete on [date] under [policy]. This record and the interview notes are the candidate's personal data, and the candidate can ask for them with a subject access request.

One page for the record where possible, two at most with dissent and adjustments.

## Try it

`examples/brackenholt-finance-decision-record.md` holds the panel's scores and notes and a draft decision record for one candidate for the Finance Business Partner role at Brackenholt Energy, a fictional 900-person energy supplier, with problems planted in the draft. When the user says "try it", "show me" or "use the example", read that file, run the check job on the draft against the panel's scores and notes, and list every problem you find before rewriting it. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-hiring-interviews), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- The decision, its date and who made it come from the user; nothing in the record proposes, softens or changes the decision.
- Every criterion has a score and at least one piece of evidence saying what the candidate said or did, and no opinion appears without evidence behind it.
- Every reason for the decision names a criterion in the scoring guide and matches the scores recorded for it; no reason for not appointing rests on a criterion the candidate scored well on.
- Nothing is unrelated to the criteria, nothing mentions or hints at a protected characteristic, health, a diagnosis, family, age, accent or where someone lives or comes from, and "culture fit" appears nowhere.
- Adjustments are recorded as what was done, with no reason or condition given.
- Who decided, when, who wrote the record, where it's held, who can see it and the deletion date are filled in, or left as placeholders listed under Check before you use it.
- Every sentence passes the subject access test: factual, about the criteria, and fine for the candidate to read.

## Guardrails

- The one rule for this pack: Claude drafts the questions, guides and letters. Interviewers gather the evidence, and people make every hiring decision. This record is written only from a decision the panel has already made and the evidence the panel supplies. Claude never proposes who to hire or fills a gap in the reasons, and leaves a visible placeholder wherever the decision or evidence is missing.
- Personal data: the record is the candidate's personal data under UK GDPR and the Data Protection Act 2018. The candidate can ask for it, with the interview notes and scores, through a subject access request, and the organisation must answer within one month. Keep it to what the decision needs, use the candidate's letter or reference in the draft, and follow your organisation's AI policy before pasting notes in. ICO guidance says not to keep unsuccessful candidates' records longer than needed; about six months is common, so follow your own policy and delete on the date.
- Fairness: the same structure, tone and level of evidence for every candidate, appointed or not. Never infer or mention a protected characteristic. Where the notes suggest one played a part, say so and advise HR review before the record is filed.
- Law: the Equality Act 2010 (direct and indirect discrimination; section 20 reasonable adjustments; positive action under sections 158 and 159), the EHRC Employment Statutory Code of Practice, UK GDPR and the Data Protection Act 2018, and ICO guidance on recruitment records and subject access. Northern Ireland has its own equality law. Check the current versions. This is a draft record, never legal advice; take advice if the candidate has raised a complaint or a claim.
- No invented facts: decisions, scores, evidence, dates and retention periods come from the user or stay as placeholders.
