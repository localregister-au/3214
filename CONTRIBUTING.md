# How to add an entry to LocalRegister

Anyone can add an entry. No technical experience required beyond what's below.

## The easy way (no GitHub account needed)

Fill in this form: *(set up a Google Form and link it here — see note at bottom)*

Submissions go to an editor, who adds them to the register within a few days using the steps below. Your submission is never altered — it's carried in as you wrote it.

## The direct way (if you have a GitHub account)

1. Go to the [`/entries`](./entries) folder
2. Click "Add file" → "Create new file"
3. Name it using the format: `YYYY-MM-DD-short-title.md` (e.g. `2026-06-19-real-deal-meeting.md`)
4. Copy the template below, fill it in
5. Scroll down, write a short note in "Commit changes" (e.g. "Add entry: refinery smell reports")
6. Click "Commit changes directly to the main branch"

That's it. Your entry is now permanently in the register, timestamped, and visible to everyone.

## Entry template

```markdown
---
title: [One sentence describing the concern]
date_raised: YYYY-MM-DD
suburb: [Corio / Norlane / North Shore / Postcode-wide]
street: [optional]
postcode: 3214
affected_postcodes: [3214] # add others if this issue spans multiple postcodes, e.g. [3214, 3220]
jurisdiction: [Local / State / Federal / Cross-jurisdictional]
issue_type: [Environment / Housing / Health & Wellbeing / Food Security / Safety / Infrastructure / Governance]
evidence_type: [Community report / Sensor data / FOI result / Media / Official document]
status: [Raised / Acknowledged / In progress / Stalled / Resolved / No response]
raised_by: [Your name, or "A 3214 resident"]
---

## What happened

[Plain description, in your own words, of what you experienced or what occurred.]

## Timeline

- YYYY-MM-DD — [what happened]
- YYYY-MM-DD — [response received, or "no response by this date"]

## Evidence

[Links to documents, sensor data, photos, screenshots, FOI outcomes, news articles — whatever supports the entry. **Every factual claim above should be traceable to something listed here.** If a source isn't linkable (e.g. a private conversation, a paywalled article, a photo not yet uploaded), say so explicitly rather than leaving it unsourced — "article behind paywall, citation: [publication, author, date, headline]" is acceptable; an unlabelled gap is not.]
```

### Sourcing standard

An entry without traceable sources is a claim, not a register entry. At minimum, every entry should include:
- A direct link, where one exists (article URL, document URL, public post URL)
- A full citation, where a direct link isn't possible (publication, author, date, headline — so the source can be independently located)
- A clear note where something genuinely can't be sourced publicly (e.g. a private conversation registered under the public-power provision in the Founding Document) — explaining *why* it's unsourced, not just leaving it blank

This isn't about distrusting submitters — it's what makes the register more credible than the institutions it's holding accountable. An entry that can be checked is worth more than one that has to be taken on faith.

### If an issue affects more than one postcode

List every affected postcode in `affected_postcodes`. The entry stays in the register where it was first raised — it isn't duplicated into other postcodes' registers. This keeps one register as the source of truth for each entry while still making cross-postcode patterns visible (e.g. an industrial site affecting both 3214 and 3220).

## What happens after you submit

Nothing is filtered out. Every entry enters the register as submitted. Editors may later mark an entry as "Highlighted" or "Pinned" if it meets the public criteria in the [Founding Document](./FOUNDING.md) — but every submission stays visible regardless.

## What never happens

Your entry is never deleted, never reworded by someone else, never hidden because an editor disagrees with it. See the Founding Document, Section Two, Principle Two.

---

*Note for setup: replace the Google Form placeholder above once a form is created. Until then, residents without GitHub accounts can message a steward directly to have an entry added on their behalf.*
