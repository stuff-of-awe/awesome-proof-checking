<!-- SPDX-License-Identifier: CC-BY-SA-4.0 -->
# Awesome Proof checking and verified proof machines

Certificate checkers, alternate kernels, mechanised metatheory, and verified executable provers are different assurance mechanisms. This collection records boundaries rather than conflating them.

**Status:** starter collection, initial review 2026-11-15. **Curator:** unassigned — contributions welcome. Entries are original short annotations of external sources, not endorsements or copies of their content. No tool was installed or executed for this initial list.

## Start here

- [CakeML verified checking](https://www.cakeml.org/checkers.html) — Understand verified certificate-checker examples and their scoped proofs.
- [SMTCoq](https://github.com/smtcoq/smtcoq) — Explore certified checkers for supported external SAT/SMT witnesses.
- [Alethe Carcara checker](https://github.com/ufmg-smite/carcara) — Find an implementation-diverse Alethe checker; it is not claimed to be formally verified.

## References and implementations

- [MetaRocq](https://github.com/MetaRocq/metarocq) — Study mechanised Rocq metatheory and verified checking/erasure.
- [Lean4Lean](https://github.com/digama0/lean4lean) — Study a Lean kernel reimplementation and its formalisation effort.
- [nanoda](https://github.com/ammkrn/nanoda_lib) — Study an independently implemented Rust checker for Lean declarations.
- [Candle](https://cakeml.org/candle/) — Read the declared scope of machine-code-level verified HOL proving.

## Examples and community routes

- [CakeML LPR checker](https://github.com/tanyongkiam/cake_lpr) — Follow an LRAT/LPR-checking case study with mechanised correctness claims.
- [VeriPB](https://veripb.org/) — Understand a pseudo-Boolean proof format and checker ecosystem.
- [Dedukti](https://github.com/Deducteam/Dedukti) — Explore logical-framework rechecking and separate translation soundness.
- [CakeML project](https://cakeml.org/) — Compare a compiler proof, an application proof and an end-to-end runtime theorem.

## First exercise (not yet execution-tested here)

Choose one proof producer and an independent checker, identify the certificate format, and document which theorem (if any) connects the executable checker to soundness.

## Assurance and interoperability

Never treat verified compilation alone as checker correctness. Record accepted input, trusted parser, theorem statement, execution semantics, and whether outputs were independently replayed.

## Scope and upstream survey

This collection exists to offer a task-oriented route through Proof checking and verified proof machines, with explicit source-level and execution-evidence boundaries. A preliminary 2026-11-15 search identified broader alternatives such as [awesome-formal-verification](https://github.com/hohieuai/awesome-formal-verification) and [formal-verification-resources](https://github.com/astrio-labs/formal-verification-resources); a comprehensive upstream awesome-list survey is still required. We have not claimed uniqueness, tested these resources, or adopted upstream text. Related categories: [Stuff of Awe catalogue](https://github.com/stuff-of-awe/.github/blob/main/docs/collections/CATALOGUE.adoc).

This list is community maintained, not a mirror or endorsement by any linked project. Please send link, licence, version and security corrections by [issue](https://github.com/stuff-of-awe/awesome-proof-checking/issues) or [PR](https://github.com/stuff-of-awe/awesome-proof-checking/pulls). Follow [curation policy](https://github.com/stuff-of-awe/.github/blob/main/docs/collections/MAINTENANCE.adoc). Text in this repository is CC-BY-SA-4.0; upstream materials retain their own licences.
