# Proposal Disclosure Schema

## Reference Statement

The Proposal Disclosure Schema (PDS) is a voluntary disclosure framework intended to improve proposal clarity, legibility, and verification.

PDS does not determine funding outcomes.
It does not assert requirements, compliance, or approval criteria.

PDS provides a structured way for applicants to make assumptions, constraints, risks, and verification surfaces explicit so that reviewers and observers can reason about proposals with fewer hidden variables.

This repository provides reference templates and examples.
It does not claim consensus, endorsement, or authority beyond its own internal coherence.

## Purpose

PDS exists to:

- Reduce ambiguity in written proposals
- Surface assumptions that are often implicit
- Separate claims from verification surfaces
- Improve reviewer and observer understanding without enforcing behavior

PDS treats disclosure as infrastructure, not as a gatekeeping mechanism.

## Scope

PDS applies to contexts where:

- Proposals request funding, resources, or delegated authority
- Outcomes must be evaluated over time
- Verification depends on artifacts rather than intent
- Reviewers must reason under uncertainty

PDS does not assume good faith or bad faith.
It assumes incomplete information.

## Voluntary and Non-Authoritative Posture

Use of PDS is optional.

- Completing a PDS does not imply approval, compliance, or endorsement
- Omitting sections does not constitute deficiency
- Non-use of PDS carries no negative signal within this framework

PDS does not bind reviewers, committees, or institutions.
It does not replace discretion.

## Schema Structure

PDS is organized into two disclosure tiers:

### PDS-Minimal

A lightweight disclosure intended for:

- Small or simple proposals
- Low-risk or short-duration work
- Requests where full disclosure overhead would be counterproductive

PDS-Minimal focuses on:

- What is being proposed
- Why it matters
- What success looks like
- What could go wrong

### PDS-Full

A comprehensive disclosure intended for:

- Complex proposals
- Long-running or high-budget work
- Systems with meaningful execution or custody risk

PDS-Full expands disclosure to include:

- Explicit scope boundaries and non-goals
- Dependency and assumption surfaces
- Risk and failure modes
- Verification methods and evidence artifacts

Applicants may choose either tier, adapt them, or mix elements as appropriate.

## Core Disclosure Dimensions

Across both tiers, PDS organizes disclosure around five dimensions:

1. Impact  
What change the proposal intends to produce and for whom.

2. Clarity  
What is in scope, out of scope, and explicitly not being attempted.

3. Alignment  
How the proposal relates to stated ecosystem or institutional goals, if any.

4. Deliverability  
What will be produced, under what constraints, and with what dependencies.

5. Verification  
How outcomes could be evaluated using observable artifacts.

These dimensions are descriptive prompts, not scoring criteria.

## Verification Versus Acceptance

PDS distinguishes between:

- Acceptance criteria  
Statements describing what completion or success would look like from the proposer’s perspective.

- Verification surfaces  
Artifacts or signals that could allow others to independently assess progress or outcomes.

Acceptance criteria express intent.
Verification surfaces support inspection.

They may overlap but serve different functions.

## Artifacts

PDS treats artifacts as evidence surfaces, not proof of merit.

Artifacts may include:

- Written specifications or documentation
- Code repositories and commits
- Test results or reproducible checks
- Milestone reports
- Deployment evidence or usage metrics

Artifacts do not include:

- Verbal assurances
- Private communications unless disclosed
- Retrospective narratives unsupported by contemporaneous records

## Examples

Examples in this repository are illustrative only.

They are derived from publicly described work and are not endorsements, evaluations, or recommendations.

Examples demonstrate how information might be disclosed, not how proposals should be judged.

## Relationship to the Process Layer Doctrine

PDS is complementary to the Process Layer Doctrine (PLD).

- PLD focuses on evaluator and system-side process hygiene
- PDS focuses on applicant-side disclosure clarity

PDS does not require PLD, and PLD does not require PDS.
They may be used independently.

## Templates

This repository provides two active disclosure templates:
- templates/minimal.md  
  For simple or low-scope proposals.
- templates/full.md  
  For complex, multi-phase, or high-uncertainty work.

Other templates are retained for historical reference only.

## Related Work

This schema complements the Process Layer Doctrine (PLD).

- PLD focuses on evaluator and system-side process hygiene.
- PDS focuses on applicant-side disclosure and clarity.

Both are optional, descriptive tools.

## Versioning and Evolution

The current version of PDS is defined in the repository root.

Versioning intent:

- Patch releases may clarify language or framing without changing disclosure intent
- Structural changes to templates require explicit version increments
- Examples may evolve independently of schema versions

Deprecated versions remain accessible for historical reference.

## Status

v0.1.1

This repository contains a reference formulation of the Proposal Disclosure Schema and illustrative examples.

No authority, mandates, or prescriptions are asserted.

## License

CC0
EOF
