# examples/nozy-example.md

Example Disclosure
NozyWallet
Illustrative Only

This is an illustrative disclosure based on the publicly described NozyWallet roadmap.
It is not a funding request.
It is not an evaluation.
It exists to surface scope boundaries, assumptions, and verification points.

Proposal Title: NozyWallet
Applicant: LEONINE-DAO / NozyWallet
Date: YYYY-MM-DD

============================================================

IMPACT

Who benefits from this, and how?

Primary beneficiaries are privacy-conscious Zcash users who want fully shielded behavior by default.
Secondary beneficiaries include the Zcash ecosystem through increased shielded usage and reduced transparent leakage.
Wallet developers benefit from a Zebra-native Orchard-only reference implementation.

What baseline does this improve on?

The baseline is existing Zcash wallets that support transparent addresses or treat shielding as optional.
This project removes transparent address support entirely and centers Orchard usage by default.

What does success look like at 6 months?

A stable Orchard-only wallet running on Zebra.
Users can create wallets, scan notes, send shielded transactions, and view balances.
Tor and I2P routing are functional and enabled.

What does success look like at 12 months?

A production-ready privacy-first wallet with maintained releases.
Shielded usage is stable.
Cross-chain and Secret Network features advance without compromising core Zcash privacy guarantees.

============================================================

CLARITY

What concrete deliverables will you produce?

- Zebra-based Orchard wallet implementation
- CLI and frontend interfaces
- Shielded transaction support only
- Secure key storage and backup
- Tor and I2P routing
- Documentation and release builds

Non-goals.
What this project intentionally does not attempt.

- Support for transparent addresses
- Custodial services
- Privacy tradeoffs for convenience
- General-purpose multi-asset wallet abstraction

Key assumptions this work depends on.

- Continued Zebra support for Orchard
- Stable Zcash network parameters
- Maintainer availability
- Community interest in privacy-first tooling

External dependencies outside your control.

- Zebra node development
- Network upgrades
- Tor and I2P network stability

============================================================

ALIGNMENT

Which values or priorities this project serves.

- Privacy by default
- Minimization of user error
- Explicit rejection of transparent usage
- Open source development

Tradeoffs you are making.
What you optimize for.
What you accept as out of scope.

Optimize for privacy correctness and safety.
Accept reduced feature breadth.
Accept slower onboarding in exchange for stronger guarantees.

How this fits within the Zcash ecosystem.

NozyWallet reinforces the intended use of Zcash shielded pools.
It complements existing wallets by providing a strict privacy-first option.

============================================================

DELIVERABILITY

Team capacity.
Realistic hours per week.

Single maintainer with sustained part-time commitment.

Timeline with milestones.

- Orchard wallet core complete
- Transaction sending and scanning
- Frontend stabilization
- Network privacy hardening
- Incremental feature expansion

Known failure modes.
What could realistically go wrong.

- Maintainer burnout
- Network changes impacting Zebra compatibility
- UX friction limiting adoption

Contingency plans if those failures occur.

- Scope reduction
- Slower release cadence
- Documentation-first stabilization

============================================================

VERIFICATION

Artifacts you expect to produce as evidence of progress.

- Public GitHub repository
- Tagged releases
- CLI binaries
- Documentation updates

Acceptance criteria.
How success will be determined.

Wallet can send and receive fully shielded transactions reliably.
Privacy routing is active.
No transparent address support exists in code paths.

Stop conditions.
Signals that the project should pause or halt.

- Inability to maintain compatibility with Zcash network upgrades
- Loss of maintainer capacity
- Privacy guarantees cannot be upheld

============================================================

END
