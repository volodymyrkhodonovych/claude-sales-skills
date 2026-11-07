---
name: post-call-follow-up
description: Drafts a B2B follow-up email after a sales, discovery or partnership call, from rough notes or a transcript. Use whenever the user shares call notes, a transcript or a call summary and wants a follow-up, recap, next-steps or thank-you email, even if they only say "write the email after my call with X".
license: MIT
metadata:
  author: Volodymyr Khodonovych
  version: "0.2.0"
---

# Post-call follow-up email

A good follow-up is short, proves you listened, and makes the next step easy. Prospects skim on mobile, so every sentence has to earn its place.

## Setup (fill in once)
- SENDER_NAME: {{your first name}}
- COMPANY_NAME: {{your company}}
- BOOKING_LINK: {{your scheduling link}}
- SIGNATURE: does the email client add it automatically? {{yes/no}}
- LANGUAGE: {{language for external emails, e.g. English}}

If any of these are still placeholders, ask for them once before drafting.

## Inputs
Ask only for what is missing:
- Call notes or transcript (any language, any state)
- Recipient name, role, company, country
- Anything promised on the call (materials, NDA, intro, date)

## Steps
1. Read all the notes. Pull out the prospect's stated problem, what was agreed, open questions, and who owes what by when.
2. Choose one thread to push forward. A follow-up that chases several topics gets no clear answer, so leave the rest out.
3. Read [references/tone-by-country.md](references/tone-by-country.md) and set formality and sign-off for the recipient's country.
4. Draft one email in LANGUAGE using the format below.
5. Check it against the rules, then deliver it with short flags: what you left out, missing names or dates, anything uncertain.

## Format
**Subject:** [Their company] × COMPANY_NAME – [specific topic]: next steps

- Open with thanks plus one specific detail from the call, which shows the notes were read.
- Recap 3–5 points of their need, in their words.
- Add 1–2 sentences on where we fit, tied to that need. Skip generic capability lists.
- List next steps with owner and date ("We: X by [date]"; "[Their company]: Y").
- End with one clear ask. The deal is active after a call, so make it specific: a concrete item or a proposed date.
- Close per the tone table. Stop there if the email client adds the signature.
- Stay under about 200 words, with short sentences and 1–2 line paragraphs.

## Links
Send links as HTML anchor text, for example `<a href="BOOKING_LINK">pick a time here</a>`, because raw URLs can be rewritten into long redirect links that look like spam. Offer BOOKING_LINK only after two concrete time slots in the recipient's time zone. If you send through a connected mail tool, open the sent message and check the link renders as anchor text.

## Rules, and why
- **One variant only.** Choosing between drafts is the user's time; a single considered draft is faster to review.
- **Only facts from the notes.** An invented number or commitment can damage trust or bind the sender to something they never said. Leave a [placeholder] for any missing name, owner or date and flag it.
- **No pricing, ROI claims or hype words.** Pricing needs context a short email can't give. If cost came up, the next step is a proposal or discovery phase.
- **No budget or funding questions.** They belong on a call, where tone and context are clear.
- **One thread per email.** Keep unrelated product lines and sensitive topics out so the ask stays clear.
- **No apologies for delay, "just checking in" or filler.** They signal low confidence and add words without adding information.
