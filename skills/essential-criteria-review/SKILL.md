---
name: essential-criteria-review
description: Checks or drafts the essential criteria in a person specification, job description or job advert for a UK role, finding requirements that could shut out people with a protected characteristic without a job reason under the Equality Act 2010, such as a degree the work doesn't need, years of experience that track age, native English speaker, a driving licence the role doesn't use, unbroken employment history, or health and fitness asks, and rewrites each as the capability the work needs, with a note of the objective justification for any requirement that stays. Use when a talent acquisition partner, recruiter or HR adviser asks to review essential criteria, check a person spec or job advert for indirect discrimination, ask whether a requirement is lawful or justified, cut down a long essentials list, or write essential and desirable criteria that keep the field open.
---

# Essential Criteria Review

Checks every essential criterion for one role with two tests: does the work need it, and could it put people who share a protected characteristic at a disadvantage? Rewrites each one that fails as the capability the job needs, and writes the justification for any that stays. Or drafts an essentials list from the job's tasks with both tests built in. It takes out the requirements that shrink the field for no job reason before the advert goes live.

## When to use

- "The hiring manager wants a 2:1 degree for this finance role. Can we justify it?"
- "Check this person spec for anything that could be indirect discrimination."
- "Is 'native English speaker' OK in an advert?"
- "Our essentials list has fifteen items. Which ones does the job really need?"
- "Write essential and desirable criteria from this job description."

Wrong tool for setting the interview criteria (Role Success Profile), checking interview questions (Question Fairness Check), or deciding whether a particular candidate meets a requirement, which is the panel's call on the evidence.

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the essential criteria as written: a person specification, an advert or the hiring manager's list. For a draft, the job description or intake record.
2. **Essential:** what the job involves day to day: main tasks, location, hours and pattern, travel and how it's done, any physical work. [taken from the job description; gaps listed as questions]
3. Any requirement set by law or a regulator: a professional qualification, a licence, vetting. [none known; each one claimed is listed to confirm]
4. The reason the hiring manager gave for each requirement, if known. [unknown; Claude proposes the likely aim and marks it to confirm]
5. Whether the organisation plans any positive action for this vacancy. [none]

Never ask for data about applicants or anyone's health, protected characteristics or contact details. The review is about the wording and the job.

## Steps

1. Read what the user has given, including attachments. If they've given a list of essentials, a person spec or an advert, this is a check job: run the review and the Quality checks on it, list every problem with where it sits and why it matters, then write corrected criteria. For a draft, write essentials and desirables from the tasks first, then put your own draft through steps 3 to 8.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If the user says "just draft it", use the defaults and list them as assumptions.
3. Apply the **job test** to every essential: could someone without it do the job well after normal induction and training? If yes, move it to desirable or cut it. Name the task that needs each essential that stays.
4. Apply the **exclusion test** to every essential left. Under section 19 of the Equality Act 2010, a requirement applied to everyone is indirect discrimination if it puts people who share a protected characteristic at a particular disadvantage and the employer can't show it is a proportionate means of achieving a legitimate aim. Look hardest at these:
   - **A degree** the work doesn't need: it can disadvantage groups less likely to hold one, older applicants among them. Write the knowledge or skill the degree stood in for, and accept other routes to it.
   - **Years of experience** ("ten years' post-qualification experience"): length of service tracks age, so it can disadvantage younger applicants. Write what those years were meant to show.
   - **"Native English speaker"** or "English as a first language": tied to national origin, so a race discrimination risk. State the level and kind of English the work needs ("writes clear papers in English for senior readers").
   - **A driving licence or own car** the role doesn't use: it can disadvantage disabled people who can't drive. Keep it only where driving is part of the work, and say how.
   - **Unbroken employment history** or "no gaps": it can disadvantage women after career breaks for caring, pregnancy or maternity, and disabled people after periods of ill health. Cut it.
   - **Health, fitness or sickness absence** asks: section 60 limits health questions before a job offer. Keep a physical requirement only where it's intrinsic to the work, write the task itself ("carries meters and tools up stairs"), and add that reasonable adjustments will be considered.
   - **Full-time only, fixed hours or short-notice availability** the rota doesn't need: these can disadvantage women, who still do most caring. State the pattern the work needs.
   - Age-coded, gendered or nationality-linked words anywhere: young, energetic, recent graduate, mature, manpower, UK-born.
5. Rewrite every requirement that fails as the capability the work needs, shown in a task: "Builds the monthly forecast with budget holders and explains the variances to them." Keep each rewrite assessable at interview, in a work sample or by a document check.
6. For every requirement that stays and could still disadvantage a group, write the objective justification in two parts: the legitimate aim (safety, a legal duty, the work itself) and why this requirement is a proportionate way to meet it, naming any less exclusionary option considered. Cost alone is unlikely to justify it. Mark each justification for the hiring manager to confirm. Where a requirement is a protected characteristic itself (an occupational requirement under Schedule 9), say it needs specialist advice.
7. Separate the conditions of employment from the criteria. Right to work is checked through the Home Office right to work check, the same way for every candidate, and is never scored; the advert names no nationality and no particular document. A qualification a regulator requires stays as an essential, with the regulator named.
8. If the user mentions positive action: sections 158 and 159 allow steps such as encouraging applications from an under-represented group, and treating one candidate more favourably only in a tie-break between candidates as qualified as each other. They never allow a quota or an essential criterion based on a protected characteristic.
9. Run the Quality checks below and fix what fails before showing anything.
10. Present the review table and the corrected criteria, then **Assumptions** and **Check before you use it**: each justification with the hiring manager, any regulator's requirement, and the hours, travel and physical work the job really has.
11. Offer a .docx, a short note for the hiring manager explaining each change in plain words, or Role Success Profile to turn the corrected essentials into four to six interview criteria.

## Output format

**Essential criteria review: [job title]**
Reviewed by [role] on [date], from [the person spec, advert or hiring manager's list].

1. **Review**

| # | As written | Job test | Exclusion risk | Action | Rewrite or justification |
| --- | --- | --- | --- | --- | --- |
| 1 | [criterion] | [needed, partly or not needed, with the task] | [the group it could disadvantage, or none found] | [keep, rewrite, move to desirable or cut] | [new wording, or the aim and why it's proportionate] |

2. **Corrected criteria**

Essential, each tied to a task:
- [capability shown in a task]

Desirable:
- [capability]

Conditions of employment, checked the same way for every candidate and never scored: [right to work; any regulated qualification or licence, with the regulator]

3. **Adjustments line for the advert**: "We'll make reasonable adjustments to the application and interview process, and to the job. Tell [contact role] what would help."

Two pages at most.

## Try it

`examples/brackenholt-finance-business-partner-person-spec.md` is the Head of Finance's draft person specification for a Finance Business Partner at Brackenholt Energy, a fictional 900-person energy supplier, with problems planted in it. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before writing the corrected criteria. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-hiring-interviews), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- Every essential that stays names the task that needs it.
- No essential asks for a degree, a number of years, a first language, a driving licence, unbroken employment, a health standard or fixed hours unless a written justification sits beside it.
- Every justification gives a legitimate aim and a reason the requirement is proportionate, and is marked for the hiring manager to confirm.
- Every rewrite is a capability shown in a task that can be assessed at interview, in a work sample or by a document check.
- Right to work appears only as a condition of employment, checked the same way for everyone, with no nationality or document named.
- No age-coded, gendered or nationality-linked wording remains.
- The corrected list carries an adjustments line.

## Guardrails

- The one rule for this pack: "Claude drafts the questions, guides and letters. Interviewers gather the evidence, and people make every hiring decision." This review tests wording against the job. Whether a candidate meets a requirement is evidence the interviewers gather, and the decision is the panel's.
- Personal data: the review needs no one's details. Work with roles, and follow your organisation's AI policy before pasting in anything about applicants.
- Fairness: apply the corrected criteria to every candidate. Never relax a requirement for one person; if a requirement changes after the advert is live, change it for everyone and tell candidates who've already applied. Never infer or mention protected characteristics.
- Law: this draws on the Equality Act 2010 (direct discrimination, section 13; indirect discrimination, section 19; reasonable adjustments, section 20; health questions before an offer, section 60; positive action, sections 158 and 159; occupational requirements, Schedule 9), the EHRC Employment Statutory Code of Practice and the Home Office guidance on right to work checks. It applies in England, Scotland and Wales; Northern Ireland has its own equality law. Whether a justification would succeed is for a tribunal, so take advice on any requirement you keep that a group could challenge. Check the current versions on legislation.gov.uk, the EHRC website and GOV.UK. This is a draft, never legal advice.
- No invented facts: tasks, reasons and regulators' requirements come from the user or stay as placeholders marked to confirm.
