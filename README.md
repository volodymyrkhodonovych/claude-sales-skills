# Claude Sales Skills

A set of [Agent Skills](https://agentskills.io) for B2B sales, organized along the sales process from first research to renewal. Plain-language, no-hype, fact-only drafting rules you can drop into Claude.

## The sales process and where each skill fits

| Stage | Skill | Use it when |
|---|---|---|
| Any | `sales-process-guide` | You describe a sales situation and want the right skill picked for you |
| 1. Research | `account-research-brief` | You want a sourced brief on a company and contact before reaching out |
| 2. First touch | `cold-outreach-email` | First email to someone who has never heard from you |
| 3. Call prep | `call-prep-brief` | You have a call coming up and want a one-page brief |
| 4. The call | `discovery-call-guide` | You want a call structure, question flow and note template for a discovery call |
| 5. Recap | `post-call-follow-up` | You have rough call notes and need the recap and next steps email |
| 6. Qualification | `deal-qualification-check` | You want to know what is confirmed, assumed or unknown about a deal |
| Any stage | `re-engagement-email` | A thread went quiet and you want to restart it |

Not covered yet: proposal, negotiation and objection handling, close planning, renewal and expansion.

## Install

Ready-made zips, one per skill, are on the [latest release](https://github.com/volodymyrkhodonovych/claude-sales-skills/releases/latest) page.

**Claude (claude.ai / desktop):** download the zip for the skill you want from the latest release and upload it under Settings → Capabilities → Skills. Check Anthropic's current docs, as menus change. To build a zip yourself, zip a skill folder (for example `skills/post-call-follow-up`) so the folder with `SKILL.md` is the zip root.

**Claude Code:** copy the folders into `~/.claude/skills/` (personal) or `.claude/skills/` (project).

## Configure

Skills with a **Setup** block contain `{{placeholders}}` (your name, company, booking link, language). Fill them in before first use. The country tone tables are starting points; adjust them to your market.

## Principles

- One variant, short, concrete.
- Only facts from your notes or cited sources. No invented numbers, clients or triggers.
- No pricing, ROI claims or hype in emails.
- Links as anchor text, never raw URLs.

## Status

Version 0.x. The skills pass the format validator, but have not been through formal test runs. Review every output before sending.

## Disclaimer

Drafts are suggestions. Follow the email-marketing and data-protection rules (for example GDPR / ePrivacy, CAN-SPAM) that apply to you; the skills do not verify legality.

## License

MIT. See [LICENSE](LICENSE).
