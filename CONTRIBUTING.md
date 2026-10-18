# Contributing to this list

Pull requests are the fastest way to get a tool added or corrected. Issues are fine too, especially for a first pass, but a PR in the right format gets picked up faster.

## Adding a new entry

1. Pick the section that actually fits. If you're not sure, say so in the PR and I'll move it if needed.
2. Match the existing format exactly:

```
- **[Tool Name](https://example.com)**: One line on what it actually does.
  Optional second line: what sets it apart, or a caveat users need to know.
  - **Best for:** the one thing this tool is genuinely best at — not a feature list.
  - **Team:** names if public, or "not publicly listed" if not. Don't leave this blank.
  - **Pricing:** what it actually costs, or "not publicly listed."
  - **Phase:** live / beta / etc.
  - **Added:** Mon YYYY · **Reviewed:** Mon YYYY
```

`Added` and `Reviewed` are the same month the first time an entry goes in — `Reviewed` only moves forward later, when the entry actually gets rechecked.

**Keep it short.** Aim for about 150 to 250 characters on the first line, and one extra line at most. Anything users need to stay safe stays in (custody, leverage risk, read-only status, AI-generated content). Feature lists, SDK and version details, and marketing copy get trimmed on merge.

**One line per field.** Best for, Team, Pricing and Phase each fit on one line (about 120 characters max). Link to a pricing or about page instead of listing every detail.

3. Open a PR against `README.md` with that entry added, in the right place in its section.

## How entries get vetted

Every submission gets checked before it goes in, PR or issue either way:

- **The tool has to be real, not vaporware.** I check the actual product, not just the pitch in the PR description. It doesn't have to be fully live — the list has a **beta** Phase for tools that are working but not yet public — but there has to be a real product behind it, not just a landing page and a roadmap.
- **No unverified performance claims.** "Guaranteed profit," self-reported win rates, or ROI numbers with no source get held until they're either removed or backed up. This list exists so people don't lose money to exactly this kind of claim.
- **Team info gets stated plainly, not spun.** If nothing's public, the entry says "not publicly listed" — that's fine, vague marketing copy standing in for it isn't.
- **Category has to actually fit.** A tool that's mostly a crypto-perps dashboard doesn't become a prediction-market tool because the PR says it is.
- **No duplicate coverage.** If something very close is already listed, the PR gets a note pointing at the existing entry rather than a silent merge.

None of this is gatekeeping for its own sake — it's the same bar I hold my own additions to. A well-sourced, honestly-described entry that fits a section usually gets merged within a few days.

## After you're merged

A star on the repo helps people find it. A link back from your own site or socials is appreciated but never required. And if you want to talk shop, I'm on Telegram at @TalHarelTal.
