<!--
Keep this body change-facing and current; replace stale facts instead of appending a diary.
Use a change-focused title without issue IDs or process tags.
Do not include internal workflow IDs, agent names, approval history, or run history.
Validation is an evidence snapshot as of one exact head. Before requesting Ready, refresh it
if the PR head changed. Filling this template does not authorize Ready, merge, or release.
-->

## Summary

<!-- What changed and why, in 1–3 bullets. -->

- 

## Scope / Non-goals

### In scope

- 

### Non-goals

- 

## Impact

<!-- State user-visible and operational impact. If none, write `None — <reason>`. -->

- User-visible:
- Operational:

## Validation snapshot

- As of exact head: `<40-character commit SHA>`
- Local:
  - `<command or manual check>` — `<result>`

<!--
`Not run` is allowed only with a reason. Add the applicable optional sections from the
source guidance below; do not leave empty rendered headings.
-->

## Author checklist

- [ ] Summary, scope/non-goals, and impact describe current facts.
- [ ] Validation is an honest snapshot for the stated exact head.
- [ ] Applicable dependency, CI, risk/rollback, artifact, or rollout evidence is included.
<!-- OPTIONAL: Uncomment only when GitHub-hosted workflows/checks exist or are expected.
## GitHub CI

- Run: `<workflow/check URL>` — `<status>` — reported head `<40-character commit SHA>`

The reported head must equal `Validation snapshot / As of exact head`.
-->

<!-- OPTIONAL: Uncomment for stacked, cross-repository, or ordered changes.
## Dependencies / merge order

- Depends on:
- Merge order:
- Merge-relevant blocker:
-->

<!-- OPTIONAL: Uncomment for behavior, data, security, infrastructure, migration,
deployment, or operational changes.
## Risks and rollback

- Risk:
- Rollback / abort:
-->

<!-- OPTIONAL: Uncomment for UI, notebook/report, publication, or rendered-output changes.
## Artifacts

- Screenshots / rendered output:
- Immutable links / digests:
-->

<!-- OPTIONAL: Uncomment only for large or new operational work.
## Operational rollout

- Repository necessity:
- Soak window: `<start> → <end>`
- Success signals:
- Abort signals:
- Result:
-->

<!-- OPTIONAL: Add at most one public or repo-local reference as the final line.
Tracking: #<repo-local issue> | <public change URL>
-->
