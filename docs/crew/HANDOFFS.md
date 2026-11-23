# Hand-offs

Each role writes only its own entries, newest at the bottom. Nobody edits another role's entry. The lead closes a finding by adding a `Closed:` line under it.

Format:

```
## H-000 | role | to: lead | date
Finding:   what is wrong, in one sentence
Evidence:  line number, selector, measured value or screenshot path
Severity:  high | medium | low
Fix:       suggested change
```

Example only. Not a real finding. The colours and numbers are made up to show the format.

```
## EXAMPLE | a11y-perf-reviewer | to: lead | 2026-11-22
Finding:   Muted label text on a card is too faint to read.
Evidence:  `.card-meta` in backpack-v3.html, grey on white measured 2.6:1 (needs 4.5:1). Screenshot: docs/crew/evidence/example.png
Severity:  medium
Fix:       darken the label colour, then re-check dark mode.
```

Real entries start below this line.

(no entries yet)
