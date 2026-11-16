# Aurelia Computational Biology Group — publication registry

This repository is the authoritative record of the group's output. Every paper is
described once in `registry.json`; a readable copy of each entry lives in
`records/<id>.md`.

## Schema (`registry.json`)

- `group_lead` — name of the group lead (the person whose personal site mirrors
  this registry).
- `records[]`:
  - `id` — internal record id (`ASB-<year>-<number>`).
  - `title` — final title of the paper.
  - `authors` — the author list as printed on the paper; each entry carries the
    author `name` and an `equal_contribution` flag.
  - `venue` — venue as it should appear in citations (full name, acronym in
    parentheses where the venue has one).
  - `year`, `date` — publication year and preprint/publication date (newest
    first when listed).
  - `cycle` — review cycle that handled the paper, `YYYY-Qn`.
  - `status` — one of `under_review`, `revise_and_resubmit`, `accepted`,
    `published`, `withdrawn`.
  - `accepted_on` — date the acceptance notice arrived (empty when not accepted).
  - `highlights` — 2 short factual bullet points about the paper.
  - `record_url` — the readable page for this record.

Group lead: Nadia Voskamp
