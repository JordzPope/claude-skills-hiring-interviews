---
name: candidate-experience-survey
description: Drafts or checks a short, anonymous candidate experience survey sent to every interviewed candidate once they've had their outcome, successful or not, asking about specific moments (the invitation, adjustments, the interviewers, the wait for an answer, feedback) and the one thing to fix, with a send plan and an analysis plan, under UK practice. Use when a talent acquisition partner, recruiter or HR adviser asks for a candidate experience survey, a candidate feedback survey, a post-interview survey, a candidate feedback form for an assessment day, questions to find out what interviewing with us is like, an alternative to a candidate NPS, or a check of an existing candidate survey before it goes out.
---

# Candidate Experience Survey

Drafts the short survey every interviewed candidate receives once they know their outcome, asking what happened at the moments that shape their view of the process: the invitation, adjustments, the interviewers, the wait for an answer and feedback. Or checks a survey someone has drafted and rewrites it. It tells you what to fix, from the people who have just been through the process, including the ones you didn't hire.

## When to use

- "We want to know what candidates think of our interviews. Write a short survey."
- "Check our post-interview survey before it goes to this month's candidates."
- "Our hiring managers think the process is fine. How do we find out what it's really like?"
- "We've started sharing questions in advance. How do we find out if it helped?"
- "Write a candidate feedback form for our assessment days."

Wrong tool for feedback to one candidate (use Candidate Feedback Note) or for reading the survey results beside the round's numbers (use Hiring Round Review).

## Inputs

Ask once for anything missing. Defaults in brackets.

1. **Essential:** the stages candidates went through and the format of each. [a video first interview, then a final interview in person]
2. **Essential:** who receives it and when. [every candidate interviewed at any stage, successful or not, two to five working days after they've been told the outcome]
3. The survey tool. [Microsoft Forms, with name and email collection switched off and one link for everyone]
4. How many candidates you expect, and the smallest group you'll report on. [results reported only for a vacancy or stage with 10 or more responses]
5. Anything you've changed recently and want to test, such as questions shared in advance or a new invitation. [none]

Never ask for candidates' names, email addresses or protected characteristics, and never add questions that collect them. Equality monitoring is a separate form with its own rules.

## Steps

Numbers in square brackets in these steps and the Quality checks are defaults. Use the user's own figure if they give one; otherwise use the default without asking.

1. Read what the user has given, including attachments. If they've given an existing survey, this is a check job: run the Quality checks on the send plan, the intro and every question, list each problem by question number with why it matters, then write the corrected survey. Keep any question that earns its place and say which ones you dropped and why.
2. Ask for missing essentials in one message, five questions at most, with the defaults shown. If the user says "just draft it", use the defaults and list them as assumptions.
3. Set who gets it and when. Send it to every interviewed candidate, successful or not, internal or external, with the same message and the same link, after they've been told their outcome. Sent before the outcome, people worry their answers will count against them. Sent only to new starters, it misses the people most likely to have had a poor experience and gives a flattering picture. Send it from the TA team's mailbox, never during an induction or a meeting, with one reminder after [five] working days and a close date [ten] working days after sending.
4. Write questions about specific moments, in the order the candidate met them:
   - **The invitation:** did it give the date, the format, who they'd meet, how long it would take and what to prepare?
   - **Adjustments:** did they know they could ask, and if they asked, were the adjustments in place? Never ask what the adjustment was or why it was needed.
   - **Questions in advance**, if you share them: did they arrive in time to help?
   - **The interviewers:** did they explain how the interview would run, give the candidate a fair chance to show what they can do, and ask only things that seemed relevant to the job?
   - **The wait:** were they told when to expect an answer, and did it arrive by then?
   - **Feedback**, where it's offered: was it specific enough to use?
   - One open question: "What one thing should we change?"
5. Use answer options that describe what happened ("Yes, all of it", "Some of it", "No") in place of star ratings or agree-or-disagree scales about feelings. Any question that might not apply gets "Doesn't apply" or "I didn't need any". Keep it to [8 to 10] questions, at most two open, under four minutes on a phone.
6. Test every question for four faults and rewrite or drop any that fail: leading wording that builds in praise ("our friendly, welcoming team"); marketing questions about the brand, its products or services, being a customer, or recommending the organisation; two questions in one; and anything that could identify the person.
7. Protect anonymity. Remove anything that identifies a respondent alone or in combination: name, email address, ATS reference, the interview date or time, the session or location in a small round, the interviewer's name, and the vacancy plus the outcome where fewer than [10] people share them. Ask about "the interviewers" as a group. Ask the stage reached only as broad options, and only where each option will reach the reporting threshold. Switch off name and email collection and response receipts in the tool, and use one link for everyone, never a link tied to the ATS.
8. Write the intro: what it's for, that it's anonymous, that the decision has already been made and nothing they say can be linked to them or change it, how long it takes, how to get another format or help to complete it, and when you'll share what you've changed.
9. Write the analysis plan: count answers per question with the base shown ("31 of 74 responded"); report only groups of [10] or more; remove names from open answers, theme them and count each theme; give each fix an owner by role and a date. Where answers point at the interviewers, read them across all panels and take the fix into the Interviewer Briefing for everyone; the survey can't fairly identify one person.
10. Run the Quality checks below and fix what fails before showing anything.
11. Present the survey, then a short **Assumptions** list and a **Check before you use it** list: the tool's settings (some form tools record names or email addresses unless you switch it off), that the outcome message goes out before the survey, who sees the raw responses, and the privacy notice line.
12. Offer a .docx, a version laid out for the user's survey tool, or the Hiring Round Review skill to read the results beside the round's numbers.

## Output format

Use the template in `templates/candidate-experience-survey.md`: the send plan, the intro, the questions in order with their answer options, a thank-you line and the analysis plan. Eight to ten questions. Every date, mailbox and threshold comes from the user or stays as a `[square-bracket placeholder]`. On a check job, the list of problems comes first.

## Try it

`examples/brackenholt-engineer-candidate-survey.md` is a draft candidate survey for the Smart-Meter Engineer vacancy at Brackenholt Energy, a fictional 900-person energy supplier, with problems planted in it. When the user says "try it", "show me" or "use the example", read that file, run the check job on it and list every problem you find before rewriting the survey. The answers are in `sample-data/answer-key.md` in the pack's GitHub repo (https://github.com/JordzPope/claude-skills-hiring-interviews), outside this skill, so the user can check your work. Use the example's facts only for this; never carry them into a draft of the user's own case.

## Quality checks

- The send plan reaches every interviewed candidate, successful or not, through the same message and link, after they've had their outcome and away from any induction or meeting.
- Each question asks about one specific moment (the invitation, adjustments, questions in advance, the interviewers, the wait, feedback) with answer options that describe what happened, plus "Doesn't apply" where it might not.
- No question is leading or marketing: no praise built into the wording, and nothing about the brand, its products, being a customer or recommending the organisation.
- No question or setting can identify a respondent: no name, email address, ATS reference, interview date, session, location or interviewer's name, and no combination of vacancy and outcome for a group under [10]. Name and email collection is off.
- The adjustments question asks only whether people knew they could ask and whether the adjustments were in place. Nothing asks about health, disability or any protected characteristic.
- There are [8 to 10] questions, at most two open, taking under four minutes on a phone, and the intro says the survey is anonymous and can't affect any decision.

## Guardrails

- The one rule for this pack: Claude drafts the questions, guides and letters. Interviewers gather the evidence, and people make every hiring decision. This survey asks about the process. Its answers never reopen or influence a decision about a candidate and never rate a named interviewer; patterns go to the TA team to fix for every panel.
- Personal data: keep the survey anonymous by default. Open answers can still hold names or details that identify someone, so remove them before pasting results into any AI tool. Survey answers that can be linked to a person are personal data under UK GDPR and the Data Protection Act 2018; follow the ICO's guidance and your organisation's AI policy.
- Fairness: make the survey accessible (plain English, works with a screen reader and on a phone, readable text size) and offer another format, or help to complete it, as a reasonable adjustment under section 20 of the Equality Act 2010. Before a job offer, section 60 allows health questions only for set purposes, such as adjustments to the process; this survey needs no health details at all, and they're special category data under UK GDPR. Equality monitoring stays on its own form, used only in aggregate, and is never joined to survey answers or to selection.
- Law: this follows the Equality Act 2010, the EHRC Employment Statutory Code of Practice, UK GDPR, the Data Protection Act 2018 and ICO guidance. Check the current versions and your own policy. This survey is a draft, never legal advice.
- No invented facts: stages, dates, response counts and thresholds come from the user or stay as placeholders.
