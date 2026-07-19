# cloud-itonami-lei-2138009tf1syomqlbj60

> **Independent third-party archive/analysis. Not affiliated with, endorsed by, or sponsored by The Go-Ahead Group Limited.**

This repository archives two publicly published documents: the **Go-Ahead
London** brand's website Terms of Use (operated by London General Transport
Services Ltd), and — the actual document that governs riding the bus, not just
browsing the website — **The Go-Ahead Group's real Conditions of Carriage**
(published via the Go South Coast subsidiary site, applying group-wide to Go-Ahead
Group member companies' UK bus/coach services). Both carry source-url and
retrieval-date provenance, per
[ADR-2607110300](https://github.com/com-junkawasaki/root/blob/main/90-docs/adr/2607110300-cloud-itonami-lei-corporate-tos-catalog.edn)
(`cloud-itonami-lei-corporate-tos-catalog`, `com-junkawasaki/root`). It is a read-only
reference/archive repository — it does not act, propose, or execute anything on the
company's behalf, and is not a governed Advisor/Governor actor.

## Company identity

- **Legal name**: The Go-Ahead Group Limited
- **LEI (ISO 17442)**: [2138009TF1SYOMQLBJ60](https://search.gleif.org/#/record/2138009TF1SYOMQLBJ60) (GLEIF-verified, status ACTIVE, registration ISSUED)
- **Jurisdiction**: GB
- **Website**: https://www.go-ahead.com (archived terms from the Go-Ahead London consumer brand, goaheadlondon.com)
- **Ticker**: unlisted (delisted from LSE Oct 2022; acquired by Kinetic Group 51% / Globalvia 49%)

## Contents

- `80-data/public/tos.journal.edn` — EDN quad-log of both archived documents (website Terms of Use + the real Conditions of Carriage).
- `NOTICE` — copyright/attribution statement for the archived third-party text.
- `blueprint.edn` — machine-readable company identity record.

## Related cloud-itonami blueprint (passenger-road-transport vertical)

Go-Ahead London operates nearly a quarter of London's bus network under contract
to Transport for London, and The Go-Ahead Group operates urban bus and rail
franchises across the UK, plus international operations (Singapore, Ireland).
This vertical's *generic, forkable* Open Business Blueprint counterpart in the
`cloud-itonami` fleet is
[`cloud-itonami-isic-4921`](https://github.com/cloud-itonami/cloud-itonami-isic-4921)
(ISIC 4921/4922 sibling pair — urban/suburban vs. intercity/chartered coach
scheduling-and-dispatch coordination, Advisor⊣Governor actor pattern). This
LEI-catalog entry is a **read-only ToS reference only** — it is not a fork of, and
has no code dependency on, isic-4921; the cross-reference exists so a reader
researching real-world urban-bus operators for market/competitive context can find
both the real company's published terms and the corresponding generic
governed-actor blueprint from one place.

## Design rationale

See ADR-2607110300 in `com-junkawasaki/root` (`90-docs/adr/`).
