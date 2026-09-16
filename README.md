# Observer

When an AI says it completed an important action, what does the evidence actually establish?

AI systems increasingly create records, receipts, screenshots, and reports about actions they claim to have completed.

Observer is an evidence-assessment approach for keeping those representations distinct from independently established outcomes.

**A representation of reality is not reality.**

## What Observer is

Observer is an evidence-assessment approach for consequential automated claims. It helps distinguish what an actor claimed, what a connector acknowledged, what a submitted artifact depicts, and what qualifying evidence supports.

Observer does not execute actions, grant authority, move money, determine fraud, provide legal conclusions, or claim omniscient truth.

## Assessment states

Observer uses three basic assessment states:

- **UNKNOWN** — the available material does not establish the required conclusion.
- **CONFIRMED** — qualifying evidence supports the claimed outcome under a defined evidence, provenance, source-family, matching, and freshness rule.
- **DIVERGED** — qualifying evidence conflicts with the defined claimed outcome.

These are assessments of evidence, not claims of omniscient truth. `CONFIRMED` is not a universal statement that something is true in the world. Do not read it as `VERIFIED`.

An actor’s own report, a connector “success” message, a screenshot, or a repeated copy of the same representation is not automatically independent evidence of the real-world outcome.

If the finding is DIVERGED, what an organization does next is a **policy** question, not an Observer finding. Observer reports what the evidence establishes. It does not lock accounts, move money, or clear a finding by generating another receipt.

## A 30-second example

Intended action: pay Vendor B $10,000 for Invoice P-4821.

| What happens | What Observer says |
|---|---|
| Agent: “I paid Vendor B.” | UNKNOWN |
| Connector/API: “Request completed.” | Not independent settlement. Execution acknowledgment only. Assessment remains UNKNOWN unless qualifying evidence arrives. |
| Screenshot shows payment | UNKNOWN |
| Ten matching screenshots | UNKNOWN, unless independence is separately established |
| Independent bank evidence: Vendor B received $10,000 | CONFIRMED |
| Independent bank evidence: Vendor C received $10,000 | DIVERGED |

See [EXAMPLE.md](EXAMPLE.md) for the same case in full.

## What this repository is

This repository is a public concept note for Observer.

It is not source code for a production system.
It is not a grant of authority.
It is not an open-source license to implement the architecture.

- [CONCEPT.md](CONCEPT.md) — representation versus reality, and the high-level loop
- [EXAMPLE.md](EXAMPLE.md) — Vendor B / $10,000 / Invoice P-4821
- [STATUS.md](STATUS.md) — what is not claimed
- [NOTICE.md](NOTICE.md) — copyright and reserved rights
