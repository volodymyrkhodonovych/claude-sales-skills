---
name: account-research-brief
description: Builds a sourced research brief on a target B2B company and contact before outreach, with recent triggers, likely priorities and a suggested first-touch angle. Use whenever the user wants to research, look into or prepare to approach a prospect company or person, asks "who is X at Y", or wants a reason to reach out, even if they never say "research".
license: MIT
metadata:
  author: Volodymyr Khodonovych
  version: "0.1.0"
---

# Account research brief

Good outreach starts with a real reason to write. This brief finds that reason in public sources and keeps facts apart from guesses, so the email that follows can be specific without being invented.

## Setup (fill in once)
- WHAT_WE_DO: {{one plain sentence on what you sell}}
- IDEAL_CUSTOMER: {{a few lines: industries, company size, roles you sell to}}

If these are still placeholders, ask once. Without them the fit assessment is guesswork.

## Inputs
Ask only for what is missing:
- Target company, and the contact's name and role if known
- Why this account is of interest, if the user has a reason

## Steps
1. Search the web for the company: what it does, size or stage if public, products, customers, recent news. Record the source and date of each finding.
2. Search for the contact: current role, tenure, public statements, talks or posts about relevant topics. Use professional sources only.
3. Look for recent, checkable triggers: funding, launches, hires, job posts, contracts, regulation, events. Prefer the last few months, since older news makes a weak opener.
4. Compare with WHAT_WE_DO and IDEAL_CUSTOMER and note the fit honestly, including where it is weak.
5. Write the brief in the format below and flag what is unverified.

## Format
- **Company snapshot:** 3–4 bullets with sources.
- **Contact:** role, tenure, one relevant public fact. Write "not found" if there is nothing.
- **Recent triggers:** dated, each with a source link. Write "none found" if there are none rather than stretching.
- **Likely priorities:** 2–3, each marked as inferred from which finding.
- **Fit:** strong, partial or weak, with the reason in one sentence.
- **Suggested angle:** one line a first-touch email could build on. Hand this to the `cold-outreach-email` skill if the user wants the email.
- **Open questions:** what the user should verify before sending.

## Rules, and why
- **Every claim carries a source and date.** The brief is only useful if the user can check it before acting on it.
- **Mark inference as inference.** A guessed priority stated as fact turns into a wrong first line in an email.
- **Public, professional information only.** Skip family, home address and personal social accounts. They add nothing to a business reason to write and can make outreach feel invasive.
- **Don't force a trigger.** If nothing real and recent exists, say so; a relevance-based email is better than a fake hook.
- **Stop and ask if the target is a private individual** rather than a business contact.
