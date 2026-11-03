---
name: situational-questions
description: Drafts or checks situational interview questions for one role, built from real incidents in the job such as competing priorities, an upset customer or a safety call, each with the facts a candidate needs, set probes, a planned twist and the points a strong answer weighs up. Use when a talent acquisition partner, recruiter, HR adviser or hiring manager asks for situational questions, scenario-based interview questions, what would you do questions, hypothetical interview questions, judgement questions, questions for candidates with no experience of the job, or wants existing scenario questions checked.
---

# Situational Questions

Produces "what would you do" questions built from the dilemmas the job really throws up, each with the facts the candidate needs, set probes and the points a strong answer weighs up. Or checks scenario questions someone already has. Candidates who've never done the job get a fair chance to show their judgement, and interviewers know what to listen for.

## When to use

- "Give me four what-would-you-do questions for our field engineers, including a safety one."
- "The hiring manager wants scenario questions for advisers with no contact centre experience."
- "Turn these real incidents from the team into interview questions."
- "Check these hypothetical questions. I think some of them give the answer away."

Wrong tool for a whole interview (use the Structured Interview Guide, which takes these questions) or for the full rating scale behind each one (use the Scoring Guide).

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the role and the criteria the questions should test. [criteria proposed by Claude from the job description, marked for you to confirm]
2. **Essential:** real situations from the job, the times it got hard, from the hiring manager or someone doing the job now, described by role. [Claude proposes typical ones for the role, marked for you to confirm with the hiring manager]
3. How many questions, and how long each. [four questions, about five minutes each with probes]
4. Who the candidates are: new to the work, experienced, or internal and external together. [a mix, including people new to the work]
5. Any procedure a strong answer must follow, such as a safety or vulnerable-customer procedure. [none given; procedure steps stay as placeholders for a qualified person to fill]

Never ask for real customers' or employees' details. If a pasted incident includes them, strip them out, change enough facts that no one could be recognised, and say you've done so.

## Steps

Numbers in square brackets in these steps and the Quality checks are defaults. Use the user's own figure if they give one; otherwise use the default without asking.

1. Read what the user has given, including any job description, incident notes or existing questions. If they've given existing questions, this is a check job: run the Quality checks on each question, list every problem with the question number and why it matters, then write corrected questions that keep the user's situations.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If the user says "just draft it", proceed on the defaults and list them as assumptions.
3. Collect the incidents. For each criterion, pick a real moment when the job got hard: competing priorities, an upset or worried customer, a safety call, a mistake to own up to, a colleague cutting a corner. If the user has none, propose typical ones and mark each "to confirm with the hiring manager". Real incidents make fairer questions than invented puzzles, and they show candidates what the work is like.
4. Find the tension. A good situational question has at least two reasonable things pulling against each other: the customer's time and the safety check, the queue and the caller who needs longer, the day's plan and an urgent job. If only one answer is sensible and the wording shows it ("Would you skip the safety check?"), every candidate gives it and the question tests nothing. Rebuild it around the real pull.
5. Write the setup in [80] words or fewer, so it can be held in mind when read aloud. Give every fact the candidate needs: who's involved, by role; what has happened; what they can see; what time pressure there is. Replace internal system names, codes and process names with what they mean ("the job app shows the customer relies on electricity for medical equipment"), so a candidate from outside has the same chance as one from inside. End with one question: "What would you do?" Show every candidate the setup in writing as well; concrete detail and a written copy help everyone, including candidates who find hypothetical questions hard.
6. Write three set probes, the same for every candidate: what they'd do first, what they'd say to the person involved, and one planned twist that tests the same criterion ("The customer says they'll complain if you leave. What now?"). No probe hints at the answer.
7. Write what a strong answer weighs up: three to five points a listener could tick off, such as safety first, being honest about what happens next, knowing when to call for help, recording what happened. Add one or two signs of a weak answer (promising what can't be delivered, ignoring the customer's worry). Where the strong answer depends on a procedure, write the principle and leave the procedure step as a placeholder for a qualified person to confirm. The full anchored scale for each criterion comes from the Scoring Guide.
8. Check the people in every scenario. Describe a customer by what they need (can't read the display, needs a carer present, relies on electricity for medical equipment, is worried about money). Never make age, disability, race, religion, sex or any other protected characteristic the source of the difficulty. Write no question about social life, after-work drinks or "fitting in"; if the user asks for a culture fit question, ask what behaviour they mean and write a scenario that tests it.
9. Run the Quality checks below and fix what fails before showing anything.
10. Present the questions, then **Assumptions** and **Check before you use it**: each incident is one that happens in this job, the strong-answer points match your current procedures (confirmed by [the qualified role] for anything safety-critical), and no setup could identify a real customer or colleague.
11. Offer a .docx, the Structured Interview Guide to place these questions in a full interview, or the Scoring Guide to anchor the ratings.

## Output format

**Situational questions: [role], [stage]**
Criteria: [list]. Time: about [minutes] per question.

For each question:

**S[n]. [criterion]** ([minutes])
Source: [the incident, by role, from the hiring manager or a job holder; or "proposed, to confirm"]
Setup (read aloud and shown in writing, 80 words or fewer): "[setup]"
Ask: "What would you do?"
Probes: 1. "[what would you do first?]" 2. "[what would you say to the person?]" 3. "[planned twist]"
A strong answer weighs up: [three to five points]
Signs of a weak answer: [one or two]
Procedure to confirm: [placeholder for the qualified role, or "none"]
Score against: Scoring Guide, criterion [n].

**Interviewer note** (three lines): read each setup as written and show the written copy; use only these probes; note what the candidate said and score each answer alone against the Scoring Guide.

## Try it

`examples/brackenholt-engineer-scenarios.md` is a field supervisor's draft scenario questions for the Smart-Meter Engineer vacancy at Brackenholt Energy, a fictional 900-person energy supplier, with problems planted in it. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before writing corrected questions. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-hiring-interviews), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- Every question comes from a real situation in the job, or one marked "to confirm", and maps to one criterion on the list. None tests culture fit, social life or anything off the list.
- Every setup has at least two reasonable actions pulling against each other, and no question's wording points to the answer.
- Every setup gives the facts needed in [80] words or fewer, with no internal system names, codes or process names a candidate from outside wouldn't know.
- Every question has three set probes, including one planned twist, the same for every candidate.
- Every question lists three to five points a strong answer weighs up, specific enough to listen for. None says "use your judgement" or "you'll know it when you hear it".
- No scenario makes age, disability, race, religion, sex or any other protected characteristic the source of the difficulty.
- In every safety scenario, the strong answer puts safety first, and any procedure step is marked for a qualified person to confirm.

## Guardrails

- The one rule for this pack: Claude drafts the questions, guides and letters. Interviewers gather the evidence, and people make every hiring decision. Claude drafts the scenarios and what to listen for. Interviewers ask them and note what each candidate says, and the panel scores against the Scoring Guide and decides. Claude never scores a candidate's answer.
- Personal data: real incidents make the best questions, so anonymise them before pasting them in: no customer names, addresses, account numbers or anything that could identify a customer or colleague. Follow UK GDPR, the Data Protection Act 2018, the ICO's guidance and your organisation's AI policy. Interviewers' notes on the answers are personal data the candidate can ask to see.
- Fairness: every candidate gets the same scenarios in the same order with the same probes. Never infer or mention protected characteristics, keep insider knowledge out of the setups, and check the wording for stereotypes.
- Law: under the Equality Act 2010 (England, Scotland and Wales; Northern Ireland has its own equality law), a written copy of the setup and extra thinking time can be reasonable adjustments under section 20, and no scenario asks about the candidate's own health or disability (section 60). See the EHRC Employment Statutory Code of Practice. For safety-critical roles these questions test judgement only; competence comes from the practical assessment and your training and sign-off under the Health and Safety at Work etc. Act 1974. Check the current versions. This is a draft, never legal advice.
- No invented facts: incidents, procedures and timings come from the user or stay as placeholders.
