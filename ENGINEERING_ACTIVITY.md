# Engineering Activity Since Day One

## Headline

**Approximately 570 estimated active engineering hours** were recorded from the first available project activity on **30 January 2026** through the snapshot on **20 September 2026**.

This represents project engineering activity across the private non-grant repository history. It is not a timesheet, invoice, employment record, or exact measure of human attention.

## Lifetime activity snapshot

| Metric | Value |
|---|---:|
| First available activity | 30 Jan 2026 |
| Snapshot activity date | 20 Sep 2026 |
| Calendar span | 234 days |
| Active development days | 116 |
| Estimated active engineering hours | 569.7 |
| Recorded work sessions | 236 |
| Included non-grant commits on canonical main history | 3,335 |
| Separate grant-only commits excluded | 5 |

## Monthly record

| Month | Recorded commits | Active days | Estimated active hours |
|---|---:|---:|---:|
| Jan 2026 | 76 | 2 | 9.3 |
| Feb 2026 | 630 | 19 | 65.9 |
| Mar 2026 | 88 | 5 | 10.7 |
| Apr 2026 | 280 | 10 | 39.5 |
| May 2026 | 683 | 13 | 111.6 |
| Jun 2026 | 272 | 18 | 67.9 |
| Jul 2026 | 906 | 27 | 167.1 |
| Aug 2026 | 250 | 10 | 53.4 |
| Sep 2026 through 20 Sep | 150 | 12 | 44.3 |
| **Total** | **3,335** | **116** | **569.7** |

## Estimation method

The calculation uses private Git metadata without publishing the underlying history.

1. Collect unique commits from the canonical main branch so temporary and duplicated private branch activity is not counted twice.
2. Exclude commits whose changed paths are entirely related to the separate grant repository work.
3. Sort the remaining commit timestamps.
4. Group activity less than 90 minutes apart into one work session.
5. Add 30 minutes per session for setup, review, and wrap-up that usually occurs around recorded changes.
6. Merge overlapping and parallel activity instead of multiplying hours across branches.
7. Cap the estimate at 12 hours per calendar day to prevent continuous automation or dense commit activity from producing impossible totals.
8. Round the public headline to 570 hours while retaining the calculated 569.7 figure in the tables.

## What the estimate includes

- Canonical mainline engineering activity, including integrated branch work
- Implemented work that was later replaced or redesigned
- Product, reliability, security, testing, documentation, and integration work
- Parallel activity collapsed onto one timeline

## What it does not prove

- Exact keyboard or screen time
- Uncommitted research, planning, meetings, design work, or manual chain operations
- Whether every recorded branch was merged
- Whether every commit represents the same amount of effort
- A direct conversion between commit volume and productivity

The estimate is intentionally conservative and reproducible from the private repository. The public repository contains only monthly aggregates, not the timestamps, identities, messages, filenames, hashes, or diffs used to calculate them.
