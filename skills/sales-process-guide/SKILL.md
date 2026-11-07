---
name: sales-process-guide
description: Routes a B2B sales task to the right skill in this set based on where the deal is, from first research to renewal. Use whenever the user describes a sales situation without naming a skill, such as "I have a new lead", "my call is tomorrow", "they went quiet" or "is this deal real", or asks what to do next in a deal.
license: MIT
metadata:
  author: Volodymyr Khodonovych
  version: "0.1.0"
---

# Sales process guide

Sales work goes in a sequence, and each stage has a different job. Picking the skill that matches the stage keeps the output useful: an outreach email is wrong for a deal that needs qualifying, and a recap is wrong for a lead nobody has contacted.

## Stage map
| Stage | What the user says | Skill |
|---|---|---|
| 1. Research | "who is X at Y", "look into this company" | `account-research-brief` |
| 2. First touch | "write an intro email", "cold email to X" | `cold-outreach-email` |
| 3. Call prep | "call tomorrow with X", "prep me" | `call-prep-brief` |
| 4. The call | "how should I run the call", "what do I ask" | `discovery-call-guide` |
| 5. Recap | "follow-up after my call", "recap email" | `post-call-follow-up` |
| 6. Qualification | "is this deal real", "why is it stuck" | `deal-qualification-check` |
| 7. Proposal, negotiation, close | (not in this set yet) | handle directly, see below |
| Any stage | "they stopped replying", "revive this thread" | `re-engagement-email` |
| 8. Renewal and expansion | (not in this set yet) | handle directly, see below |

## How to route
1. Identify the stage from what the user describes. If two stages fit, choose the earlier one that hasn't been done.
2. Read the matching skill's SKILL.md and follow it.
3. Mention in one line which stage this is and what typically comes next, so the user sees the sequence.
4. If the stage has no skill, help directly with the shared principles below and say that no dedicated skill exists yet.

## Shared principles
These run through every skill in the set. Apply them when working without a dedicated skill:
- Use only facts from the user's notes or cited sources. Invented numbers and references damage the sender's credibility.
- Ask for one clear next step per message.
- Keep external messages short and plain, since buyers read on mobile.
- Don't promise results or quote prices in early messages.
- Mark assumptions and flag what the user should verify before sending anything externally.
