---
name: not-progressing-email
description: Drafts or checks the set of messages that tell candidates they are not progressing, one for each stage of a hiring process (after application, after a first interview, after a final interview, plus a holding update when a decision runs late), each with a send-by timescale, a human tone, an offer of feedback where policy allows, and consent wording before anyone's details are kept for future roles, under UK practice. Use when a talent acquisition partner, recruiter, recruitment coordinator or HR adviser asks for rejection emails, unsuccessful candidate emails, regret letters, ATS rejection templates, a message for candidates who didn't get through the interview, a way to stop ghosting candidates, or a check of their current rejection templates and timings.
---

# Not Progressing Email

Drafts the messages a hiring process needs so that every candidate who stops at any stage hears from a person, by a date the team can keep: after application, after a first interview, after a final interview, and a holding update when a decision runs late. Or checks the current templates and timings and rewrites them. It replaces the ATS default that goes out late, or never.

## When to use

- "Our ATS rejection emails sound like a robot wrote them. Rewrite them."
- "We need messages for each stage of our contact centre hiring so nobody's left hanging."
- "What should we send people who didn't get through the first interview?"
- "Check our rejection templates and the timings we've set in the ATS."
- "Candidates are complaining they never heard back after the assessment day."

Wrong tool for individual feedback written from the panel's notes (use Candidate Feedback Note) or for the invitation that sets expectations at the start (use Interview Invitation).

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the stages where a candidate can stop, and roughly how many reach each one. [application, first interview, final interview]
2. **Essential:** your feedback policy at each stage. [none after application; short feedback on request after a first interview; written feedback offered after a final interview]
3. Who sends each message, and how. [the recruitment coordinator through the ATS after application; the talent acquisition partner by email after a first interview; after a final interview, the hiring manager calls and the talent acquisition partner emails the same day]
4. Whether you keep details for future roles, and for how long. [no; records deleted at the end of your retention period]
5. The vacancy, so each message can name the role and stage. [placeholders]

Never ask for candidates' names, contact details or the reasons behind individual decisions. If the user pastes a candidate's details, use a letter instead and say so.

## Steps

Numbers in square brackets in these steps and the Quality checks are defaults. Use the user's own figure if they give one; otherwise use the default without asking.

1. Read what the user has given, including attachments. If they've given existing templates, an ATS set-up or a process timeline, this is a check job: run the Quality checks on each message and on the timeline, list each problem with the message and line it sits in and why it matters, then write the corrected set.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If the user says "just draft it", use the defaults and list them as assumptions.
3. Map every point where a candidate can stop: after the application is screened, after any test or task, after each interview, and when a vacancy is filled, paused or withdrawn. For each, set the trigger, the sender by role, the channel and a send-by deadline in working days: [five] after the screening decision, [three] after a first interview, and [two] after a final interview, with a call first. Any stage with no message is a gap to close. In a late-2025 OnePoll survey of 1,000 UK workers for Employment Hero, 42% said they'd been ghosted after an interview, and this timeline is what keeps your candidates out of that number.
4. Add the holding update. When a decision will miss the date the candidate was given, send a short message by that date with a new date. Two lines are enough.
5. Write each message from one person to one person. Open with their first name and the role, and give the decision in the first two sentences. Keep it short: [120] words at most after application, [180] after an interview. Thank them for something specific to the stage (the application, a 30-minute video call, a morning at the assessment centre). Sign it with a person's name and role and a reply address someone reads.
6. Take out cold template language and say the thing plainly. Remove "Dear Applicant", "Dear Candidate", "we regret to inform you", "your application has been unsuccessful", "due to the high volume of applications", "please do not reply to this email", team-only sign-offs and any no-reply sender.
7. Give a reason only if it's true for everyone stopped at that stage and tied to the published criteria ("we've invited the applicants whose answers showed [criterion] most clearly"). Remove any reason that could be discriminatory under the Equality Act 2010: age-coded words ("energy", "overqualified"), "native speaker", gaps in work history, full-time or shift availability the job doesn't require, family commitments, health, and "culture fit". Each risks a claim of direct or indirect discrimination, and a template repeats the risk with every send.
8. Offer feedback where the policy allows: how to ask, by when, and who replies. After a final interview, the hiring manager or talent acquisition partner calls first; the email confirms the same day and offers written feedback.
9. Handle future roles. "We'll keep your CV on file" needs a lawful basis under UK GDPR, and the candidate must be told. Replace it with a consent question: what you'd keep, for which kind of role, for how long, how to agree (a reply) and how to change their mind later. With no reply, the details are deleted at the end of your retention period. Follow the ICO's guidance on keeping recruitment records and your own policy.
10. Keep each message the same for every candidate at a stage, including anyone who had adjustments, and never mention an adjustment. Use plain text that reads well on a phone and with a screen reader, and add a line on how to ask for another format.
11. Write the ATS notes: the merge fields used ([first name], [role], [stage date]), the sender set to a named person's monitored mailbox, and the trigger for each message.
12. Run the Quality checks below and fix what fails before showing anything.
13. Present the timeline and the messages, then a short **Assumptions** list and a **Check before you use it** list: that the team can meet each deadline at current volumes, your feedback policy, the retention period and the privacy notice wording, and that the reply address is monitored.
14. Offer a .docx, plain-text versions to paste into the ATS, the Candidate Feedback Note skill for candidates who ask for feedback, or the Candidate Experience Survey skill to find out how the new messages land.

## Output format

Use the template in `templates/not-progressing-messages.md`: the stage timeline, one message per stage, the holding update, the call notes for the final stage, the future-roles consent wording and the ATS notes. Every timescale, policy and sender comes from the user or stays as a `[square-bracket placeholder]`. On a check job, the list of problems comes first.

## Try it

`examples/brackenholt-customer-adviser-rejections.md` holds the ATS set-up and current rejection templates for Customer Adviser hiring at Brackenholt Energy, a fictional 900-person energy supplier recruiting 30 advisers for its Sheffield contact centre, with problems planted in it. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before rewriting the messages and the timeline. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-hiring-interviews), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- Every point where a candidate can stop has a message, a sender by role and a send-by deadline in working days, and a holding update covers any decision that will miss its date. No interviewed candidate waits more than [five] working days for an answer or an update.
- The decision is in the first two sentences, from a named person in a role, with a reply address someone reads.
- No cold template language: no "Dear Applicant" or "Dear Candidate", "regret to inform", "high volume of applications", "do not reply" or no-reply sender.
- Any reason given is true for everyone at that stage and tied to the published criteria. None touches a protected characteristic or a proxy for one (age-coded words, accent or "native speaker", gaps in work history, availability the job doesn't require, family commitments, health), and none says "culture fit".
- Feedback is offered where the policy allows, with how to ask, by when and who replies.
- No "we'll keep your CV on file" or talent-pool line appears without asking for the candidate's agreement, saying what's kept and for how long, and how to say no.
- Messages run [120] words at most after application and [180] after an interview, and are the same for everyone at a stage apart from the merge fields.

## Guardrails

- The one rule for this pack: Claude drafts the questions, guides and letters. Interviewers gather the evidence, and people make every hiring decision. These messages tell candidates about decisions people have already made. Claude never decides who progresses, never sorts candidates into messages, and never adds a reason the decision-makers didn't give.
- Personal data: work with templates and merge fields, never candidate lists. Keeping a candidate's details for future roles needs a lawful basis under UK GDPR and the Data Protection Act 2018, and the candidate must be told; asking for their consent is the plain route. Follow your organisation's AI policy and the ICO's guidance on how long to keep recruitment records.
- Fairness: every candidate at a stage gets the same message on the same timescale, internal or external, whatever their background. Check each reason and phrase for language that could amount to direct or indirect discrimination under the Equality Act 2010, and never mention an adjustment someone had under section 20.
- Law: this follows the Equality Act 2010, the EHRC Employment Statutory Code of Practice, UK GDPR, the Data Protection Act 2018 and ICO guidance. Check the current versions and your own policy. These are drafts, never legal advice.
- No invented facts: timescales, policies, retention periods and sender details come from the user or stay as placeholders.
