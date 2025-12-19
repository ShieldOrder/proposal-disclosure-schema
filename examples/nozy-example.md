# Example Disclosure — NozyWallet (Illustrative)

This is an illustrative disclosure derived from the publicly described NozyWallet roadmap.
It is not a funding request and does not imply evaluation.
Its sole purpose is to make assumptions, scope, and verification surfaces explicit.

Proposal Title: NozyWallet — Fully-Shielded Orchard Wallet on Zebra  
Applicant: LEONINE-DAO / NozyWallet  
Date: YYYY-MM-DD

======================================================================

IMPACT

Who benefits from this, and how?

Primary beneficiaries are privacy-conscious Zcash users who want fully shielded behavior by default.
Secondary beneficiaries include other wallet developers, who gain a Zebra-native, Orchard-only reference implementation.
Wallet developers benefit from a Zebra-native, Orchard-only reference implementation.

What baseline are you improving against?

Existing Zcash wallets support transparent addresses or treat shielding as optional.
Indexing and note handling behavior varies across implementations.
Users are often exposed to privacy footguns through defaults rather than explicit choice.

What does success look like at 6 months?

A production-usable Orchard-only wallet running on Zebra.
Reliable note scanning, balance calculation, and transaction history for shielded addresses.
Clear user education surfaces explaining shielded behavior and privacy guarantees.

What does success look like at 12 months?

Stable frontend release with fully shielded defaults.
Documented and reproducible Orchard indexing behavior.
Operational Tor and I2P routing enabled by default.
Active users conducting fully shielded transactions without touching transparent addresses.

======================================================================

CLARITY

Explicit deliverables you will produce:

A Zebra-based Orchard-only wallet implementation.
Deterministic Orchard note scanning and balance calculation.
CLI and frontend interfaces with privacy-first defaults.
Encrypted local storage and secure key management.
Documentation explaining design decisions and privacy tradeoffs.

Non-goals.
What this explicitly is not:

A wallet supporting transparent addresses.
A performance-optimized indexer for unbounded historical scanning.
A general-purpose multi-asset wallet UI.
A consensus or protocol change.

Key assumptions this depends on:

Stability of Orchard semantics under NU 6.1.
Continued availability of Zebra as a maintained full node.
Feasibility of deterministic Orchard indexing on consumer hardware.

External dependencies outside your control:

Upstream Zebra changes affecting indexing or RPC behavior.
Protocol changes impacting Orchard note handling.
Network reliability for Tor and I2P routing.

======================================================================

ALIGNMENT

Core values this project serves:

Privacy by default, not by configuration.
Elimination of transparent leakage paths.
User education through explicit design constraints.
Deterministic, auditable wallet behavior.

Tradeoffs you are making:
What you optimize for.
What you optimize against.

Optimizing for privacy correctness and user safety.
Optimizing against backward compatibility with transparent workflows.
Accepting higher resource usage in exchange for stronger guarantees.

How this fits the Zcash ecosystem:

Increases shielded pool usage.
Provides a reference for Orchard-only wallet design.
Complements Zebra as a Rust-based, production-grade node.
Aligns with Zcash’s privacy-first mission.

======================================================================

DELIVERABILITY

Team capacity.
Realistic hours per week:

Single primary developer, approximately 15–25 hours per week, subject to availability.

Timeline with milestones:

Phase 1: Core wallet infrastructure and Orchard support.
Phase 2: Deterministic indexing, transaction history, and balance logic.
Phase 3: Frontend integration and user education surfaces.
Phase 4: Privacy network hardening and advanced features.

Known failure modes.
What could go wrong:

Indexing complexity exceeds initial assumptions.
Edge cases in reorg handling introduce state inconsistencies.
Multi-chain features dilute focus from core Zcash functionality.

Contingency plans:

Constrain indexing scope to bounded ranges.
Explicitly document unresolved edge cases.
Defer non-Zcash integrations until core stability is proven.

======================================================================

VERIFICATION

Evidence artifacts you will produce:

Public source code repository.
Reproducible builds and test instructions.
Demonstrable shielded transaction flows.
Screenshots or logs showing Orchard-only behavior.
Documentation of assumptions and invariants.

Acceptance criteria.
How success will be determined:

Users can create wallets, receive funds, send funds, and view balances without touching transparent addresses.
Repeated scans of the same block range produce consistent results.
All network calls route through configured privacy layers.

Stop conditions.
When the project would halt:

If deterministic Orchard indexing cannot be achieved reliably.
If upstream protocol changes invalidate core assumptions.
If privacy guarantees cannot be upheld without unacceptable compromise.

======================================================================

NOTES

Some sections may remain partially incomplete.
This reflects genuine uncertainty and active development.

The purpose of this disclosure is legibility, not persuasion.
