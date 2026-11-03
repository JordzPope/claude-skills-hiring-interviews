---
name: candidate-ai-use-statement
description: Drafts or checks a candidate-facing statement on using AI in a UK hiring process, stage by stage, with what AI use is fine (preparing, polishing a CV, accessibility tools), what isn't (answers generated live in an interview, someone else taking part), how the interview checks fairly through follow-up questions and explaining your own work, and which tools the organisation itself uses on candidates' information. Use when a talent acquisition partner, recruiter or HR adviser asks for a candidate AI policy, an AI use statement for applicants, rules on ChatGPT or AI in interviews, careers site or invitation wording about AI, what to tell candidates about AI on a take-home task, or a check of an existing candidate AI statement.
---

# Candidate AI Use Statement

Produces the short statement candidates read before they apply or interview: what AI use is fine at each stage, what isn't, how the interview tells the difference, and which tools you use on their information. Or checks a statement someone has already written. Clear rules let honest candidates use the tools they rely on, and give the panel one fair, open way to check.

## When to use

- "We need something on the careers site about candidates using ChatGPT."
- "Our developers think half the take-home tasks are written by AI. What do we tell candidates?"
- "Write an AI statement to link from the invitations for the software roles."
- "Check our candidate AI policy. It reads like a threat."
- "Can we just ban AI in our hiring process?"

Wrong tool for how the panel checks identity or live help on the day (use Interview Integrity Plan) or for your own staff's AI policy. This statement is the candidate's side; the Integrity Plan is the panel's.

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the stages of your process and what each involves: application, any online test or take-home task, interviews (video or in person), any live task. [application, one video interview, one in-person interview]
2. **Essential:** what AI use you're happy with at each stage, if you've decided. [preparing and polishing are fine at every stage; answers in a live interview or test must be the candidate's own; a take-home task follows its own instructions]
3. Any tools your organisation uses on candidates' information: AI features in the ATS (CV summaries, matching, ranking), transcription or note-taking in interviews, video interview platforms, online tests. [none known; confirm with whoever owns the ATS]
4. The checks your interviewers actually make: follow-up questions, explaining a take-home in the interview, cameras on for video, identity checks at interview. [follow-up questions and explaining your own work]
5. Where the statement will appear and who candidates contact. [the careers site, linked from every invitation; the talent acquisition team]

Never ask for candidates' names or details of any candidate suspected of using AI. The statement is the same for everyone.

## Steps

Numbers in square brackets in these steps and the Quality checks are defaults. Use the user's own figure if they give one; otherwise use the default without asking.

1. Read what the user has given, including any existing statement, take-home instructions, privacy notice or ATS details. If they've given an existing statement, this is a check job: run the Quality checks on it, list every problem with where it sits and why it matters, then write a corrected statement.
2. Ask for missing essentials in one message, five questions at most, showing the defaults. If they say "just draft it", use the defaults, leave the tools table as a placeholder and list the assumptions.
3. Write what's fine, stage by stage, with plain examples: using AI to research the organisation, practise answers or polish a CV and cover letter, as long as what it says about the candidate is true. Name assistive and accessibility tools as fine (screen readers, dictation, captions, text-to-speech, spelling and grammar support), and say that any tool agreed as an adjustment is fine at every stage, with a contact to ask.
4. Write what isn't, as specific behaviour at a named stage: having AI generate answers during a live interview or test; reading out answers someone or something else is feeding in; someone else sitting a test, doing a task or taking part in the candidate's place; and for a take-home, whatever its own instructions rule out. Replace any blanket ban ("no AI at any stage") with stage-by-stage rules. A blanket ban catches spelling checkers and accessibility tools, contradicts take-home tasks that allow AI, and can't be followed or checked.
5. Write how the interview checks, using only the checks the user confirms their interviewers make: follow-up questions on any answer; asking candidates to explain their own work, choices and trade-offs; cameras on for video interviews unless an adjustment says otherwise. Say what happens when the panel has a concern [the panel asks more questions, or invites the candidate to a short follow-up conversation], and that it's the same for every candidate. Remove any claim about detection software, eye tracking, audio monitoring or recording the user hasn't confirmed, and ask before keeping one.
6. State any consequence once, plainly and in proportion, and only if the process has one, for example that an application may not go further if someone else took part in an interview. Remove threats, "we will know", bans from future applications and wording that treats every candidate as a suspect.
7. List the tools the organisation uses on candidates' information: what each does, at which stage, and whether a person checks its output. Link the candidate privacy notice. UK GDPR requires candidates to be told how their information is used. If a tool scores, ranks or filters candidates, tell the user that DSIT's *Responsible AI in Recruitment* guide (March 2024) says to check it against reasonable adjustments, consider whether its use is automated decision-making under Article 22 of UK GDPR and run a data protection impact assessment, and that their data protection lead should see the wording first. The ICO's November 2024 audit outcomes report on AI recruitment tools sets out what it expects on data minimisation, transparency and fairness. Write "We don't use AI tools on your application" only once the user has confirmed it with whoever runs the ATS and the interview platforms.
8. Keep it short and even in tone: under [350] words, about reading age 12, "you" and "we". Open with why it exists (so candidates know where they stand, and every candidate is treated the same). Leave out statistics about candidate fraud.
9. Run the Quality checks and fix what fails.
10. Present the statement and a one-line version for invitations, then **Assumptions** and **Check before you use it**: that the tools list is complete (ask whoever owns the ATS and the video platform), that every check named is one your interviewers really make, that the take-home rules match the task's instructions, the privacy notice link, and the adjustments contact.
11. Offer a .docx, the Interview Invitation skill to carry the one-line version, or the Interview Integrity Plan skill for the panel's side.

## Output format

**Using AI in our hiring process**

[One or two sentences: why this exists, and that it applies to every candidate.]

**AI use that's fine**
- [Stage]: [plain examples]
- At every stage: assistive and accessibility tools. Any tool agreed as an adjustment is always fine. To ask for one, contact [role] at [contact].

**AI use that isn't**
- [Stage]: [specific behaviour]

**How our interviews check**
[The checks your interviewers really make.] If the panel has a concern, [what happens], and this is the same for every candidate.

**Tools we use on your information**

| Tool | What it does | At which stage | Does a person check it? |
| --- | --- | --- | --- |
| [tool] | [what it does] | [stage] | [yes, and how] |

People make every hiring decision. Our candidate privacy notice explains how we use your information: [link]. You can ask for the information we hold about you, including interview notes.

**Questions:** [contact role and contact]

Under [350] words. One-line version for invitations: "Using AI: preparing and polishing are fine, your answers in the interview must be your own, and agreed accessibility tools are always fine. Read more: [link]."

## Try it

`examples/brackenholt-developer-ai-statement.md` is an engineering manager's draft AI statement for Software Developer hiring at Brackenholt Energy, a fictional 900-person energy supplier, with the facts about the process at the top and problems planted in the draft. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before rewriting the statement. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-hiring-interviews), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- Every rule names a stage and a behaviour a candidate can follow without guessing, and there's no blanket ban on AI or "any tools".
- Assistive and accessibility tools are named as fine, tools agreed as adjustments are fine at every stage, and there's a contact to ask.
- Every check described is one the user has confirmed their interviewers make, and no claim of detection, monitoring, eye tracking or recording stands unconfirmed.
- Every tool the organisation uses on candidates' information is listed with what it does and whether a person checks it, the privacy notice is linked, and the statement says people make every hiring decision.
- Any consequence is stated once, plainly, and applies to every candidate the same way, with no threats, future bans or "we will know".
- The rules for each stage match that stage's own instructions, so a take-home that allows AI isn't banned elsewhere in the statement.
- No fraud statistics or vendor figures appear, and the statement is under [350] words.

## Guardrails

- The one rule for this pack: Claude drafts the questions, guides and letters. Interviewers gather the evidence, and people make every hiring decision. This statement sets the same rules for everyone. Interviewers gather the evidence through follow-up questions, and people make every decision, including what happens when there's a concern about AI use.
- Personal data: the statement carries no candidate data. Never paste in details of a candidate suspected of using AI; use the Interview Integrity Plan skill with candidate letters. Describe truthfully every tool that processes candidates' information. Follow your organisation's AI policy.
- Fairness: the same rules and the same checks for every candidate. Blanket bans and suspicion fall hardest on disabled candidates who rely on assistive tools and on anyone who uses spelling or grammar support, so keep those tools clearly allowed. Never infer or mention protected characteristics, and never single out a group of candidates for extra checks.
- Law: UK GDPR and the Data Protection Act 2018 (tell candidates about any tool used on their information; interview notes are personal data and can be requested through a subject access request); the ICO's AI recruitment audit outcomes report (November 2024) and DSIT's *Responsible AI in Recruitment* guide (March 2024); section 20 of the Equality Act 2010 (reasonable adjustments, including assistive technology), the Act's rules on indirect discrimination for a rule that disadvantages disabled candidates, and the EHRC Employment Code. Check the current versions. This is a draft, never legal advice.
- No invented facts: tools, checks and consequences come from the user or stay as placeholders. Never describe monitoring the user hasn't confirmed, and never quote figures on candidate fraud.
