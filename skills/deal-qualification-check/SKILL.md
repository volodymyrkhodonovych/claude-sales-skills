---
name: deal-qualification-check
description: Checks how well one B2B deal is qualified from call notes and email history, marking each key element as confirmed, assumed or unknown, and proposes the next questions. Use whenever the user asks whether a deal is real, why it is stuck, what is missing to move it forward, or to review or qualify an opportunity, even if they never say "qualification".
license: MIT
metadata:
  author: Volodymyr Khodonovych
  version: "0.1.0"
---

# Deal qualification check

Deals stall on the facts nobody confirmed. This check shows what you actually know about a deal, separated from what you hope is true, and turns each gap into a question for the next conversation.

## Inputs
Ask only for what is missing:
- Call notes, transcripts or email threads for the deal
- The company, the contacts and their roles
- The current stage in the user's own words

## Steps
1. Read everything provided. Quote or closely paraphrase what the buyer said, as opposed to what the seller said.
2. For each element below, mark it **confirmed** (the buyer said it or did it), **assumed** (the seller believes it, with no buyer statement), or **unknown**, and attach the evidence.
3. Identify the two or three gaps most likely to stop the deal.
4. Turn each gap into one open question the user can ask next, in a form a buyer finds easy to answer.
5. Recommend one next action and flag anything you could not verify from the notes.

## Elements
- **Problem:** what the buyer says is wrong, in their words.
- **Impact:** what it costs them, with any number the buyer gave. Never supply a number the buyer didn't.
- **Decision maker:** who can approve, and whether we have spoken to them.
- **Decision process:** the steps, people and timeline the buyer described.
- **Buying criteria:** how they will compare options.
- **Internal advocate:** someone inside who wants this to happen and has influence.
- **Alternatives:** other vendors, an in-house build, or doing nothing.
- **Next step:** the last agreed action, with owner and date.

## Format
A table with element, status, and evidence, followed by the top gaps, the questions, and the recommended next action. Keep it to one page. A table fits here because the reader scans for gaps.

## Rules, and why
- **Only the notes count as evidence.** A confident score built on missing information gives false comfort and hides the real risk.
- **Don't produce a numeric probability or forecast category.** Notes can't support one, and a made-up number gets repeated as fact.
- **Treat the seller's optimism as assumed.** "They love us" without a buyer statement or action is assumed.
- **No budget or pricing questions in the suggested questions** unless the buyer raised cost. Frame them around impact and process first.
- **Say so when the notes are too thin to judge**, and list what to collect instead.
