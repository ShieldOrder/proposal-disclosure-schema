cat > examples/nozy-example.md <<'EOF'
This document is an illustrative example of a completed disclosure.
It does not imply endorsement, approval, or recommended structure beyond the underlying template.

# Example Disclosure
NozyWallet
Illustrative Only

This is an illustrative disclosure based on the publicly described NozyWallet roadmap.
It is not a funding request.
It is not an evaluation.
It exists to surface scope boundaries, assumptions, and verification surfaces.

Proposal Title: NozyWallet
Proposer or Team: LEONINE-DAO / NozyWallet
Date: YYYY-MM-DD

============================================================

IMPACT

Who is expected to benefit from this work, and how?

Primary beneficiaries are privacy-conscious Zcash users who want shielded behavior by default.
Secondary beneficiaries may include the Zcash ecosystem through increased shielded usage and reduced transparent leakage.
Wallet developers may benefit from a Zebra-native Orchard-only reference implementation.

What existing baseline does this improve upon?

The baseline is existing Zcash wallets that support transparent addresses or treat shielding as optional.
This work removes transparent address support entirely and centers Orchard usage by default.

From the proposer’s perspective, what would success look like after approximately 6 months?

An Orchard-only wallet operating on Zebra.
Users can create wallets, scan notes, send shielded transactions, and view balances.
Tor and I2P routing are functional.

From the proposer’s perspective, what would success look like after approximately 12 months?

A maintained privacy-first wallet with published releases.
Shielded usage remains stable.
Additional features advance without compromising Zcash privacy guarantees.

============================================================

CLARITY

What concrete outputs or deliverables are expected?

- Zebra-based Orchard wallet implementation
- CLI and frontend interfaces
- Shielded transaction support only
- Secure key storage and backup
- Tor and I2P routing
- Documentation and tagged releases

Non-goals.
What this work explicitly does not attempt.

- Support for transparent addresses
- Custodial services
- Privacy tradeoffs for convenience
- General-purpose multi-asset wallet abstraction

Key assumptions this work depends on.

- Continued Zebra support for Orchard
- Stable Zcash network parameters
- Maintainer availability
- Ongoing community interest

External dependencies outside the proposer’s direct control.

- Zebra node development
- Network upgrades
- Tor and I2P network stability

============================================================

ALIGNMENT

Which values, goals, or priorities this work is intended to serve.

- Privacy by default
- Minimization of user error
- Explicit rejection of transparent usage
- Open source development

Tradeoffs being made.
What is optimized for.
What is accepted as out of scope.

Optimize for privacy correctness and safety.
Accept reduced feature breadth.
Accept slower onboarding in exchange for stronger guarantees.

How this work relates to existing efforts within the Zcash ecosystem.

It reinforces the intended use of shielded pools.
It complements existing wallets by providing a strict privacy-first option.

============================================================

DELIVERABILITY

Team capacity and availability.

Single maintainer with sustained part-time commitment.

Indicative timeline or phases.

- Orchard wallet core completion
- Transaction sending and scanning
- Frontend stabilization
- Network privacy hardening
- Incremental feature expansion

Known risks or failure modes.

- Maintainer burnout
- Network changes impacting Zebra compatibility
- UX friction limiting adoption

Potential responses or mitigations.

- Scope reduction
- Slower release cadence
- Documentation-first stabilization

============================================================

VERIFICATION

What artifacts are expected to be produced that could allow others to observe progress or outcomes?

- Public code repositories
- Tagged releases
- CLI binaries
- Documentation updates

Acceptance criteria.
How outcomes might be assessed.

Wallet demonstrates the ability to send and receive fully shielded transactions reliably, as observed through testing or user reports.
Privacy routing remains active.
No transparent address support exists in code paths.

Stop or pause signals.

- Inability to maintain compatibility with network upgrades
- Loss of maintainer capacity
- Inability to uphold stated privacy guarantees

============================================================

END
EOF
