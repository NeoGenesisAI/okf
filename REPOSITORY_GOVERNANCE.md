# Repository Governance Contract

Policy ID: `ng-repo-governance/1.0.0`
Last reviewed: 2026-08-27

## Identity

- Repository: `Yesol-Pilot/neogenesis-okf`
- Lifecycle class: `company-operating-framework`
- Current owner: `Yesol-Pilot`
- Intended owner: `NeoGenesisAI`
- Canonical branch: `master`
- Canonical-branch target: `main`
- Visibility: `public`
- Production status: `UNKNOWN`
- Transfer state: `REQUIRED`

`UNKNOWN` means not independently verified and must never be reported as PASS.

## Purpose and current risk

NeoGenesis OKF is a public company operating framework or policy surface. Public process documents can become de facto authority, so versioning, scope, supersession, evidence, exceptions, and relationship to actual runtime systems must be explicit.

- Active consumers, authoritative versions, superseded documents, implementation status, public claims, and review cadence remain `UNKNOWN`.
- A written framework does not prove that autonomous agents, products, or business units implement it.
- Normative requirements, guidance, examples, experiments, and historical material must be distinguishable.
- Personal, credential, internal incident, customer, or private repository information must not leak into public policy examples.

## Required remediation

- [ ] Define authoritative documents, semantic versions, owners, scope, implementation mappings, supersession, exceptions, review cadence, and consumers.
- [ ] Run full-history secret, license, public-claim, personal-data, link, and document-drift audits.
- [ ] Add schema or document validation, internal-link, version, supersession, implementation-reference, example-safety, publication, and rollback checks.
- [ ] Separate policy author, implementation owner, independent verifier, exception approver, and public publisher roles.
- [ ] Mark unimplemented requirements and historical material explicitly; prohibit framework text from being presented as operational proof.
- [ ] Normalize `master` to `main` only after public links and consumers are verified, then transfer to `NeoGenesisAI`.

## Pull-request and branch rules

- One task, one branch, one isolated worktree.
- Draft inactivity limit: 14 days; maximum stack depth: 3.
- PRs declare normative scope, version, supersession, implementation, public-claim, exception, and rollback impact.
- Review conversations resolve before squash merge.
- Canonical branches are not force-pushed or deleted.

## Exit criteria

The repository becomes `TRANSFERRED_COMPLIANT` only when organization ownership, authoritative versioning, implementation mapping, explicit exceptions, public safety, link integrity, review cadence, consumer migration, and rollback are proven.

The presence of this file alone is not compliance.
