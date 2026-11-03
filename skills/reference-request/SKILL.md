---
name: reference-request
description: Drafts or checks a reference request to a candidate's referee in a UK organisation, with factual questions tied to the role's criteria, sent only with the candidate's consent and at the stage the organisation's policy allows (usually after a conditional offer), with no health or sickness absence questions before an offer, and a plain statement of how the reference will be used and kept. Use when a talent acquisition partner, recruiter, recruitment coordinator or HR adviser asks for a reference request email or letter, reference check questions, an employment reference form, what to ask a referee, whether they can ask a referee about sickness absence, or a check of their reference template.
---

# Reference Request

Writes the request a referee receives: who you are, that the candidate has agreed, factual questions linked to the criteria the panel assessed, how the reply will be used and kept, and when you need it back. Or checks a reference form that's been in use for years. A short, specific request gets answered sooner, and the answers are more use to the person deciding.

## When to use

- "We've made a conditional offer to Candidate A. Write the reference request to their last two employers."
- "What should we ask referees for the smart-meter engineer roles?"
- "Can we ask a referee about sickness absence?"
- "Check our reference form. It hasn't been updated in years."
- "Write a short reference request a busy line manager will actually answer."

Wrong tool for deciding whether a reference is satisfactory, which a person does under the offer's conditions, or for right to work, criminal record or qualification checks, which have their own processes. For the record of the panel's decision, use Decision Record.

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the role and its criteria, from your Role Success Profile or Scoring Guide.
2. **Essential:** the stage, and the referees the candidate has named and agreed to you contacting. [after a conditional offer, with the candidate's written consent for each referee they've named]
3. The type of referee. [the most recent line manager for the criteria questions; HR at that employer for dates and job title]
4. What you need confirmed. [dates of employment, job title and main duties, plus up to four questions linked to the criteria]
5. Deadline and how to reply. [five working days, by email to the recruitment coordinator]
6. How references are used and kept under your policy. [read by the recruitment coordinator and the hiring manager; kept on the personnel file for the person who starts; deleted six months after the decision if the offer doesn't go ahead]

Never ask for the candidate's or referee's names or contact details at the drafting stage; they stay as placeholders for the user to fill in. Never ask for anything about the candidate's health or protected characteristics.

## Steps

1. Read what the user has given, including any existing form, offer letter or criteria. If they've given an existing request or form, this is a check job: run the Quality checks on it, list every problem with where it sits and why it matters, then write a corrected version.
2. Ask for missing essentials once, in one message, five questions at most, with the defaults shown. If the user says "just draft it", use the defaults and list them as assumptions.
3. Confirm consent and stage before anything else. The candidate must have named this referee and agreed to the contact, at the stage your policy allows, usually after a conditional offer, so a current employer hears nothing before the candidate is ready. If consent isn't confirmed, draft a short consent request to the candidate first and hold the referee letter, with `[Candidate's consent for this referee confirmed on: date]` at the top. Never suggest contacting anyone the candidate hasn't named.
4. Write the factual section: dates of employment, job title and main duties, so the referee can confirm the application. Many employers give only dates and job title as policy; say in the letter that this is fine.
5. Write one question for each criterion, up to four, asking what the referee saw the candidate do at work: "This role involves [real task from the criterion]. Can you tell us about a time the candidate [did something comparable] while working with you? What did they do?" Keep the referee to what they observed. Replace every opinion question about personality or character ("How would you describe their personality?", "Are they a team player?", "Rate their attitude out of 10", "Would they fit in?") with a question about work the referee saw.
6. Keep health and absence out. Before an offer, section 60 of the Equality Act 2010 stops an employer asking about health, apart from narrow purposes such as adjustments to the interview, and that includes asking a referee about health or sickness absence. After a conditional offer, health questions go to occupational health or a health questionnaire under your policy, handled as special category data, and stay out of the reference. Take out any question about age, family, caring, pregnancy, religion or any other protected characteristic. If the role has a genuine requirement, such as an on-call rota, ask every candidate directly whether they can meet it, and consider adjustments.
7. For safety-critical or regulated roles, check qualifications and registrations at the source, using certificates or the issuing body's register, and keep the referee questions to the criteria.
8. Write the handling paragraph: what the reference is for (confirming the facts and the criteria for a conditional offer for [role]), who will read it by role, how long it's kept, and that the candidate may be able to see it through a subject access request. Check ICO guidance on references for when that applies.
9. Write a short note for your own file on what happens next: a named role reads the reference against the criteria, and if anything in it could lead to withdrawing the offer, the candidate gets a chance to respond before a person decides.
10. Run the Quality checks and fix what fails before showing anything.
11. Present the consent request if it's needed, then the referee request and questions, then **Assumptions** and **Check before you use it**: that consent is on file for each referee, the stage your policy allows, the reply date, and the retention period in your privacy notice.
12. Offer a .docx, a phone version for referees who prefer to talk (the same questions with space for notes), or the Decision Record skill.

## Output format

**Consent request to the candidate** (only if consent isn't yet confirmed): four to six lines asking the candidate to confirm which referees you may contact, and when.

**Reference request**

Subject: Reference request for [candidate name], [role], [organisation]

Dear [referee name],

[Candidate name] has accepted a conditional offer for the role of [role] at [organisation] and has named you as a referee. They agreed to us contacting you on [date].

**Part 1: please confirm**

| Question | Answer |
| --- | --- |
| Dates of employment | |
| Job title | |
| Main duties | |

If your organisation's policy is to confirm dates and job title only, please complete Part 1 and say so.

**Part 2: about their work** (please answer from what you saw)

1. [Criterion 1]: [question about what the referee saw the candidate do]
2. [Criterion 2]: [question], and so on, up to four.

**How we'll use your reply**: read by [roles] to confirm the facts and the criteria for this role, and kept for [period] under our privacy notice ([link]). The candidate may be able to see what you write if they make a subject access request.

Please reply by [date] to [role and email address]. Thank you for your help.

[Sender role], [organisation]

**For your file: what happens next**: [the role who reads the reference and against which criteria; how a concern is raised with the candidate before anyone decides]

Under a page.

## Try it

`examples/brackenholt-engineer-reference-form.md` is the reference request email and form Brackenholt Energy, a fictional 900-person energy supplier, uses for its Smart-Meter Engineer roles, with problems planted in it. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before rewriting the request. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-hiring-interviews), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- The request records the candidate's consent for this referee with a date, and goes out at the stage the user's policy allows (after a conditional offer, by default); without consent, the consent request comes first and the referee letter is held.
- Every question after the factual section links to a named criterion and asks what the referee saw the candidate do at work.
- No question asks about health, disability, sickness absence or absence records, and none asks about age, family, caring, pregnancy, religion or any other protected characteristic.
- No question asks for the referee's opinion of the candidate's personality, character or "fit", or for a rating of a trait.
- The request says what the reference is for, who will read it, how long it's kept and that the candidate may be able to see it.
- The request gives a reply date and a way to reply, and accepts an answer that confirms only dates and job title.
- The candidate's and referee's names and contact details stay as placeholders.

## Guardrails

- The one rule for this pack: Claude drafts the questions, guides and letters. Interviewers gather the evidence, and people make every hiring decision. This request gathers facts for people to weigh. Claude never judges whether a reference is good enough or what it means for the offer; a named person decides that, after the candidate has had a chance to respond to any concern.
- Personal data: a reference is personal data about the candidate, and the request shares their details with a third party, so contact only referees the candidate has named and agreed to. Under UK GDPR and the Data Protection Act 2018, tell the referee how the reply will be used and kept, keep it for your retention period only, and follow your organisation's AI policy before pasting a reference into Claude. Health information is special category data and stays out of references.
- Fairness: the same questions, stage and handling for every candidate who reaches this point, internal or external. Never infer or mention a protected characteristic. If a referee volunteers something about health, family or another protected characteristic, set it aside, keep it out of the decision and take HR advice.
- Law: the Equality Act 2010 (section 60 on health questions before an offer, which covers asking a referee; direct and indirect discrimination; section 20 reasonable adjustments), the EHRC Employment Statutory Code of Practice, UK GDPR and the Data Protection Act 2018, and ICO guidance on references and recruitment records. Right to work checks follow Home Office guidance and are a separate step. Northern Ireland has its own equality law. Check the current versions. This is a draft request, never legal advice.
- No invented facts: criteria, dates, deadlines and retention periods come from the user or stay as placeholders.
