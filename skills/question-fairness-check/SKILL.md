---
name: question-fairness-check
description: Checks a set of interview questions against UK law and good practice and rewrites the ones that fail, flagging questions that touch health or disability before an offer, age, marriage or civil partnership, pregnancy or family plans, religion, nationality or other protected characteristics, questions about culture fit, leading or double-barrelled questions, and insider jargon that favours internal candidates. Also drafts fair wording for asking every candidate about a job's real requirements, such as shifts, travel, driving or physical tasks. Use when someone asks to check interview questions, review questions for bias or discrimination, find illegal or unlawful interview questions, ask about availability or sickness lawfully, make questions fair to internal and external candidates, or get a list of questions to avoid.
---

# Question Fairness Check

Checks a set of interview questions and lists every one that's unlawful, unfair, leading or written for insiders, with the reason and a rewrite that tests the same thing fairly. Or drafts fair ways to ask about a job's real requirements. Hiring managers get a set of questions they can ask every candidate in the same words.

## When to use

- "Can you check the hiring manager's questions before Thursday's panel?"
- "Is it OK to ask candidates about their sickness record?"
- "We've got internal and external candidates for the team leader role. Are these questions fair to both?"
- "How do I ask about the late shift without asking about childcare?"
- "Review our standard interview questions for bias."

Wrong tool for writing a whole interview (use the Structured Interview Guide, then run its questions through this check) or for replying to a candidate who asks for an adjustment (use the Adjustment Request Reply).

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the questions to check, pasted or attached; or, for a draft job, the job's real requirements (shift pattern, travel, driving, lifting, working at height, security checks). [no default; this is the one thing Claude needs]
2. The role and the criteria the questions should test. [read from the questions themselves, marked for you to confirm]
3. Who's applying: internal candidates, external candidates, people new to the work. [internal and external together]
4. Any small talk or extra questions interviewers tend to add on the day. [none]
5. Whether the organisation uses positive action (such as a guaranteed interview scheme) or Success Profiles. [neither]

Never ask about any candidate, or for what any candidate answered. The check is on the questions alone.

## Steps

1. Read what the user has given, including any attached guide, question list or interviewer notes template. If they've given questions, this is a check job: go through every question, list each problem with the question number and why it matters, then write a corrected set. If they've given only the job's requirements, this is a draft job: write the fair wording in step 7 and run the Quality checks on it.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If the user says "just draft it", proceed on the defaults and list them as assumptions.
3. For every question, name the criterion it tests. A scored question that tests nothing on the criteria list is flagged for removal.
4. Check for protected characteristics and health questions under the Equality Act 2010:
   - **Health or disability before an offer (section 60):** sickness absence record, conditions, medication, time off for appointments, "anything we should know about your health". Before an offer these are allowed only for set purposes, such as adjustments to the interview itself or whether someone can do a task intrinsic to the job; most organisations keep health questions until after a conditional offer. Asking is a breach the EHRC can enforce, and acting on the answer can be disability discrimination. Rewrite to the adjustment question ("Is there anything we can do to make today work better for you?") or to the task itself.
   - **Age:** date of birth, when they left school, "how long until you retire?", "digital native", "young team", "managing people older than you".
   - **Marriage or civil partnership, pregnancy, family plans, caring:** partners, children, childcare, plans for a family. Rewrite to the working pattern itself, asked of everyone: "The role covers the late shift until 9pm one week in four. Can you work that pattern?"
   - **Religion or belief:** faith, places of worship, religious holidays. Availability for the real rota is asked of everyone in the same words.
   - **Nationality, race, accent, "where are you from?":** never asked at interview. Right to work is confirmed through the Home Office right to work check, done for every candidate at the point your policy sets.
   - **Sex, gender reassignment, sexual orientation:** any question about relationships, appearance or identity.
   Outside section 60, the risk sits in the answer: if a candidate is turned down after a question about a protected characteristic, the question can be used as evidence of discrimination. Remove them all.
   Two areas sit outside the Equality Act: trade union membership (refusing a job because of it is unlawful under the Trade Union and Labour Relations (Consolidation) Act 1992) and criminal records (ask only what your policy and the Rehabilitation of Offenders Act 1974 allow, and leave it to the formal check).
5. Check how each question is built:
   - **Leading:** the wording shows the answer the panel wants ("You'd be comfortable with that, wouldn't you?"). Rewrite as an open question asking for an example.
   - **Double-barrelled:** two questions in one ("How do you handle stress, and what motivates you?"). Split it, or keep the half that tests the criterion. A STAR question with its set probes counts as one question.
   - **Culture fit:** any question or criterion about fitting in, being "one of us", hobbies or social life. Ask what behaviour is meant and rewrite to that.
   - **Insider jargon:** internal system names, acronyms, process names, team nicknames or "the way we do it here". These favour internal candidates and people from the same sector. Put the facts in plain words inside the question. Keep a technical term only when the criterion is job knowledge and every candidate was told in advance what to prepare.
   - **Off-script:** a question one interviewer adds, or a question asked only of some candidates. Every candidate gets the same questions.
6. Rewrite every flagged question to test the same criterion: plain words, open, one thing at a time, the same for every candidate. If a question tests no criterion, write "remove" and give no rewrite. Switch any he or she for the job holder to "they" and say so.
7. For each real requirement behind a flagged question (and for the draft job), write the fair way to ask it: state the requirement, then ask whether the candidate can meet it, with adjustments if they need them. "The job includes climbing a ladder to reach some meters. Can you do that, with adjustments if you need them?" If the organisation uses positive action, keep it within sections 158 and 159 and out of the questions themselves.
8. Run the Quality checks below and fix what fails before showing anything.
9. Present the report, then the corrected question set, then **Assumptions** and **Check before you use it**: the criterion each question is meant to test, the real working pattern and job requirements, when your right to work checks happen, and your policy on health questions after an offer.
10. Offer a .docx, an "ask this, avoid this" sheet for the Interviewer Briefing, or the Structured Interview Guide to put the corrected questions in order with probes and timings.

## Output format

**Question fairness check: [role], [stage]**

**Flagged questions**
| # | Question as written | Problem | Why it matters | Rewrite, and the criterion it tests |
| --- | --- | --- | --- | --- |
| [n] | "[original]" | [e.g. health before an offer, section 60] | [one or two lines] | "[rewrite]" ([criterion]), or Remove |

**Questions that pass**: [numbers], each with the criterion it tests.

**Corrected question set**: every question in order, ready to use.

**Asking about the job's real requirements** (draft job, or where a flagged question was getting at one)
| Requirement | Ask every candidate | Avoid |
| --- | --- | --- |
| [e.g. late shift until 9pm, one week in four] | "[fair wording]" | "[the question to drop]" |

One page plus the corrected set.

## Try it

`examples/brackenholt-team-leader-questions.md` is a contact centre manager's draft panel questions for the Team Leader, Customer Operations vacancy at Brackenholt Energy, a fictional 900-person energy supplier, where internal and external candidates are interviewed together, with problems planted in it. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before writing the corrected set. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-hiring-interviews), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- Every question that touches health, disability or sickness absence, age, marriage or civil partnership, pregnancy, family or caring, religion or belief, sex, gender reassignment, sexual orientation, race or nationality is flagged with the law it engages and removed or rewritten.
- No health question remains before an offer except for a purpose section 60 allows, and right to work is left to the Home Office check, done for every candidate.
- No question is leading or double-barrelled.
- No question depends on internal system names, process names or acronyms that only insiders would know; the facts needed are in the question itself.
- No question or criterion is "culture fit"; each is rewritten to the behaviour meant.
- Every rewrite tests the same criterion as the original, or the original is marked for removal because it tests none.
- Every question is accounted for: flagged with a rewrite, marked for removal, or listed as passing.

## Guardrails

- The one rule for this pack: Claude drafts the questions, guides and letters. Interviewers gather the evidence, and people make every hiring decision. Claude checks and rewrites the questions. Interviewers ask them and gather the evidence, and the panel decides. Claude never looks at what a candidate answered or judges a candidate.
- Personal data: the check needs the questions only, with no candidate names, answers or notes. Follow your organisation's AI policy. If answers to a flagged question have already been recorded, keep them out of the decision and take advice on what to do with them; they're personal data under UK GDPR and the Data Protection Act 2018, the candidate can ask to see them, and they're kept only as your retention policy and the ICO's guidance on recruitment records allow.
- Fairness: every candidate gets the same questions in the same words. Never infer or mention protected characteristics, and check the wording for idioms, assumptions about who does the job, and references only one group would know.
- Law: the Equality Act 2010 applies in England, Scotland and Wales (Northern Ireland has its own equality law): direct and indirect discrimination, section 20 reasonable adjustments, section 60 health questions before an offer, and sections 158 and 159 positive action. See the EHRC Employment Statutory Code of Practice, the EHRC's guidance on pre-employment health questions, Acas guidance on recruitment and the Home Office guidance on right to work checks on GOV.UK. Check the current versions. This is a draft, never legal advice; take advice if a flagged question has already been asked and a candidate has raised it.
- No invented facts: working patterns, job requirements and policies come from the user or stay as placeholders.
