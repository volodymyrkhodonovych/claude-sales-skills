---
name: discovery-call-guide
description: Gives a live B2B discovery call structure, with an opener, an ordered question flow, a note-taking template and a closing next-step ask. Use whenever the user is about to run, is running, or wants to improve a discovery or first sales call, or asks how to run the call, what to ask, or how to capture notes, even if they never say "discovery".
license: MIT
metadata:
  author: Volodymyr Khodonovych
  version: "0.1.0"
---

# Discovery call guide

A discovery call has one job: learn the buyer's situation well enough to know whether and how you can help. Buyers open up when the seller listens more than pitches, so this guide keeps the call question-led and leaves clean notes for the follow-up.

## Inputs
Ask only for what is missing:
- Who is on the call and the call length
- Any research or prep brief (the `call-prep-brief` skill produces one)
- Whether the user wants a plan before the call or a note template to use during it

## Call flow
1. **Open (2 min).** Thank them, confirm the time, and state a simple agenda: learn about their situation, share briefly how you work if relevant, agree next steps. Ask whether that works for them. This sets expectations and gives them control.
2. **Situation (spend the most time here).** Ask open questions about how things work today, what they have tried, and who is involved. Start broad and narrow only after they answer.
3. **Problem and impact.** Ask what is not working and what it costs them in time, money or risk. Use their words and numbers; never offer figures for them.
4. **Decision.** Ask how a decision like this gets made, who else is involved, and what has to happen first. Ask this naturally, not as a checklist, so it doesn't feel like an interrogation.
5. **Alternatives.** Ask what else they are considering, including doing nothing.
6. **Brief fit (only if asked or clearly useful).** Describe in one or two sentences how you could help, tied to what they said.
7. **Close.** Summarize in two or three sentences to confirm you understood, then propose one specific next step with a date.

## Notes template
Capture these during the call so the follow-up writes itself:
- Their stated problem, in their words
- Impact they gave, with any numbers
- People involved and their roles
- How they decide, and the timeline they mentioned
- Alternatives mentioned
- What was promised, by whom, by when
- Open questions

When the call is over, hand the notes to the `post-call-follow-up` skill.

## Rules, and why
- **Ask, then listen.** Pitching before you understand the problem makes the buyer defensive and gives you nothing to follow up on.
- **One question at a time.** Stacked questions get partial answers.
- **No pricing and no budget questions in a first call** unless the buyer raises cost. These shut conversations down before value is clear.
- **Never invent numbers or case studies** to fill a silence. Say you will check and follow up.
- **Confirm before assuming.** Repeat back what you heard on the important points; wrong assumptions found now are cheap, later they are expensive.
