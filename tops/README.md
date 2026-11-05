# TOPs Daily Brief (Talent Operations only)

A TOPs-only routine, fully separate from the TA daily reporting routine.

| | |
|---|---|
| Schedule | Weekdays 8:43 AM SGT (scheduled task "TOPs Daily Brief") |
| Sources | TOPS Base (`app0ELsaxiLjfR75D`): Onboarding + Off-Boarding tables; shared mailbox `talentoperations@manifest.inc` |
| Mode | Read-only: never sends email or edits Airtable |
| Output | Brief in the session + push notification |
| Prompt | [`tops-daily-brief-prompt.md`](tops-daily-brief-prompt.md) |

What's in the brief: Do-today checklist · upcoming joiners with missing
items · offboarding pipeline (SA / LOE / assets) · shared-mailbox threads
waiting on TOPs · probation ending ≤14 days · data-hygiene flags
(offer accepted but no onboarding form, stale statuses, duplicates).

Needs the **Airtable** and **Microsoft 365** connectors attached to the
scheduled task.
