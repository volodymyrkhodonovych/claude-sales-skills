---
name: re-engagement-email
description: Drafts a short email to restart a B2B sales thread that has gone quiet, after first checking whether re-engaging is the right move. Use whenever the user mentions a stalled, ghosted or cold lead, asks to revive, nudge, reconnect or follow up on a silent thread, or asks which threads need attention, even if they never say "re-engagement".
license: MIT
metadata:
  author: Volodymyr Khodonovych
  version: "0.2.0"
---

# Re-engagement email

Most quiet threads need the right question, not more persuasion. The methods here are common practitioner heuristics (interest questions over meeting requests, very short plain-language emails, Dean Jackson's 9-word email, Chris Voss's "Have you given up on…?"). They are patterns that tend to work, not guarantees.

## Setup (fill in once)
- SENDER_NAME: {{your first name}}
- COMPANY_NAME: {{your company}}
- BOOKING_LINK: {{your scheduling link}}
- SIGNATURE: does the email client add it automatically? {{yes/no}}
- CRM_BCC: {{optional BCC address for CRM logging}}

## Inputs
- Lead: first name, company, country
- The full email history with the company. Search by domain and contact names and read every thread, including meeting recaps.
- What the prospect originally wanted, in their words. If you can't find it, ask the user. A guessed need produces an email that sounds generic and gets ignored.

## Step 0: decide whether this is a re-engagement
- **Whose move is it?** If the last open action item is ours (a demo, data, an answer), this is a progress update in the existing thread, not a re-engagement.
- **Did they close it?** If they said no, "on hold indefinitely", "at capacity" or declined, report the thread as closed and restart only on real news.
- **Is it really quiet?** If there was contact in the last two weeks or so, wait.
- When scanning several threads, report each status (re-engage / update / closed / wait) before drafting anything.

## Steps
1. Read all threads with the company. Note what they wanted, what we offered, every email sent since their last reply, and which hooks were already used.
2. Count unanswered touches per company, across all contacts. Counting per person would restart the ladder every time you switch contact.
3. Pick one topic to restart and leave other tracks out.
4. Choose the email type from the ladder.
5. For a trigger email, find a real, unused reason to write with a quick web search: news about them (product, funding, contract, programme change, event, key hire), something new on our side that matches their stated need, or an event where you could meet. News older than your last meeting doesn't count. If nothing real and fresh exists, move to the next rung. An invented reason is worse than none.
6. Draft one email. For tone and sign-off, read [references/tone-by-country.md](references/tone-by-country.md).
7. Deliver it with flags: the ladder step and why, the reason used with its source, anything assumed or missing.

## The ladder (unanswered touches per company)
- **Touch 1, trigger email (max 60 words).** Line 1: the real news about them. Line 2: how it links to their stated need. Line 3: an interest question ("Is [their goal] still on your roadmap?"). No calendar link.
- **Touch 2, 9-word email.** Subject: their first name. Body: "Are you still [their goal in their words]?" and nothing after it. Use it only if they showed real interest before.
- **Touch 3+, Voss close.** Subject: their first name. Body: "Have you given up on [their project]?" and nothing else. If a fresh, unused hook exists, use one line of news plus a priority question ("With [news], where does [their project] sit on your priority list today?").
- **No reply after the Voss close:** stop. The thread stays closed until real news appears.
- **When they reply positively:** offer two concrete time slots in their time zone, checked against your calendar, with BOOKING_LINK as a fallback.

## Format
- Subject: new and specific (trigger) or first name only (9-word, Voss). Don't reuse "Re:" on the old thread and don't write "Following up". Progress updates go in the existing thread.
- Greeting and sign-off per the tone table. Stop after the closing line if the client adds the signature.

## Links
Send links as HTML anchor text, for example `<a href="BOOKING_LINK">pick a time here</a>`, because raw URLs can be rewritten into long redirect links that look like spam. If you send through a connected mail tool, open the sent message and check the link renders as anchor text.

## Rules, and why
- **Interest questions only in touches 1–3, no calendar links until they reply.** A meeting request asks for time before interest is confirmed, which is the usual reason dormant threads stay silent.
- **Ask about their project or goal**, never "are you still interested in working with us". The first is easy to answer; the second invites a polite no.
- **Plain words, short sentences, 1–2 line paragraphs.** Most email is read on mobile.
- **Never reuse a reason from earlier emails.** A repeated hook reads as automation.
- **No apology for the gap, no "just checking in", no "circling back", no guilt.** They add pressure without adding a reason to reply.
- **Only real facts, with a source for any news.** Don't claim certifications or results you can't confirm.
- **No ROI claims, hype words, pricing or budget questions.** Those belong on a call.
- **One variant only.**
