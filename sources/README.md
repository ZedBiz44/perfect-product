# Source inventory and migration notes

[Repository home](../README.md)

Imported September 29, 2026 from the user-supplied [Perfect Product page](https://app.notion.com/p/3e9a3e33d58181c6a57ed01f725ddf7a).

## Scope

- Root page and all 13 direct subpages.
- Nested Facebook Research page under Grok Research.
- Groups & Offers database: all 47 records, with no remaining query page.
- Every database record was fetched separately; each had a blank page body.
- Both database references in Grok Research use the same data source and are represented once.

## Files

- [manifest.json](notion/manifest.json): source URLs, document paths, last-edited timestamps, and counts.
- [export.json](notion/export.json): original connector output for 15 pages, database schema, and complete query results.
- [database-pages.json](notion/database-pages.json): original fetch output for the 47 individual records.
- [Readable database](../docs/research/groups-and-offers.md): all returned property values organized by record.

The raw JSON retains Notion's enhanced Markdown, properties, source paths, and available verification metadata. Readable documents convert tables, callouts, and imported page references into GitHub Markdown. Links to pages outside the requested subtree remain Notion links and were not recursively imported.

The connector returned no truncation or unknown-block warnings for the imported material. Comments, revision history, and unrelated linked workspace pages are outside this snapshot. No Notion content was changed.

## Interpretation

The decision guide and repository navigation are editorial additions. Source documents retain rejected ideas and later corrections. Repository folder placement is organizational, not an assertion that every claim in a document is current.

Prices, audience counts, revenue estimates, market assertions, and third-party quotations are historical source material, not independently verified findings from this migration. Preserve their source dates and caveats.

This is a one-time snapshot, not an automatic Notion sync. For subsequent updates, retain dated corrections and record which source changed. Review imported text before republishing because the destination repository is public.

## September 29 repository review

Grok bot’s review, supplied by Jack in the follow-up chat, is recorded in [exploration gaps](../docs/research/exploration-gaps.md). The hopper, ingredient table, status banners, and blank experiment worksheets are editorial additions based on that review and the preserved source verdicts. They do not add buyer evidence or change the raw Notion snapshot.
