# Scores ledger

Catalog numbering v2 (2026-09-30): IDs now match Notion group order. Only identifiers and links changed; scores, confidence and reasoning retain their original meaning. See the [old-to-new map](catalog-id-map.md).

[Repository home](../../README.md) · [Product catalog](../products/README.md) · [Perfect Product Rubric](../framework/perfect-product-rubric.md) · [Decision guide](../current-direction.md)

**Purpose:** Record ten-bar assessments for catalog ideas so agents use one scoring system. This ledger does **not** change catalog Type or Status.

## How agents score

1. **Review the [Perfect Product Scoring Guide — Assumptions and Interpretation](https://app.notion.com/p/3eba3e33d58181d19eabc5d62f6401f4) first.** Use guide v1.2 and its pinned rubric/definition commits for concept scoring, reasonable assumptions and confidence.
2. Read the [Perfect Product Rubric](../framework/perfect-product-rubric.md) and [definition](../framework/perfect-product.md) for the ten criteria. Rubric v1.1 defines all score thresholds; guide v1.2 explains how to apply them. Score only when Jack or the task asks.
3. Save each dated independent assessment in its own reviewer folder with a summary, CSV and individual sheets. Record the guide version, assessed product version, assumptions, reasons and confidence as required by the guide. Preserve earlier assessments; Grok's original [CSV](index.csv) and [sheets](sheets/) now use aligned catalog-v2 IDs; their earlier paths remain available in the migration map and Git history.
4. Use the [shared leaderboard](leaderboard.md) to compare assessments. Show each reviewer's concept-fit assessment separately. Combine only in a labelled reconciliation under the guide; never average U with numbers. Keep earlier evidence assessments separate.

The guide is maintained in Notion. This ledger links to it rather than maintaining a second copy of the procedure. Existing scores and catalog statuses are unchanged.

## Files

| File | Role |
| --- | --- |
| [leaderboard.md](leaderboard.md) | Shared comparison across independent assessments; individual results; combination only after labelled reconciliation |
| [index.csv](index.csv) | Grok's original machine-readable scores for all 41 entries |
| [sheets/](sheets/) | Grok's original evaluation sheets for catalog IDs 01–41 |

## Related

- [Product catalog README](../products/README.md)
- [Ingredient register](../ingredients.md)
- [Current direction](../current-direction.md)


## Independent assessments

- [Grok — 2026-09-29: all 41 ideas](grok-2026-09-29/README.md), moved from the former leaderboard, with the original [CSV index](index.csv) and [individual sheets](sheets/).
- [Cody — 2026-09-30: all 41 ideas](cody-2026-09-30/README.md), with a separate [CSV index](cody-2026-09-30/index.csv) and individual sheets. Grok's scores remain unchanged; identifiers have been aligned.
- [Mary — 2026-09-30: all 41 ideas](mary-2026-09-30/README.md), with a separate [CSV index](mary-2026-09-30/index.csv) and individual sheets. Grok's and Cody's score values remain unchanged; identifiers have been aligned.
- [Mary — 2026-09-30, guide v1.1: re-score of all 41 ideas](mary-2026-09-30-guide-v11/README.md), with [CSV index](mary-2026-09-30-guide-v11/index.csv) and individual sheets; saved as a new dated assessment under concept-fit rules; Grok's, Cody's and Mary's original assessments remain unchanged.
- [Z3 — 2026-09-30, guide v1.1: all 41 ideas](z3-2026-09-30/README.md), with [CSV index](z3-2026-09-30/index.csv) and 41 individual sheets. Z3 scored independently before reading other reviewers' score sheets.
- [Manus — 2026-09-30, guide v1.1: all 41 ideas](manus-2026-09-30/README.md), with [CSV index](manus-2026-09-30/index.csv) and 41 individual sheets; independently scored under the same concept-fit rules. Historical reviews and the Mary/Z3 v1.1 records remain unchanged.
