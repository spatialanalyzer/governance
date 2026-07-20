# Governance

## 1. Provisional model

The project uses a consensus-based, maintainer-led model during its founding
stage. This document is a working policy and may be refined as the community
grows.

The word **maintainer** describes a project role. It does not mean ownership of
copyrights, trademarks, funds, repositories, or other assets. Likewise,
GitHub's "organization owner" permission is an access-control designation and
does not independently grant governance or intellectual-property rights.

## 2. Founding roles

The initial roles are:

- **Project Founder and Lead Architect** — a Founding Maintainer responsible
  for the architectural direction of the Briosa product family.
- **Hexagon Primary Focal** — a Founding Maintainer appointed by Hexagon and
  Hexagon's principal representative for project decisions.
- **Hexagon Backup Focal** — a Founding Maintainer appointed by Hexagon who
  participates in project work and acts as the alternate for the Primary Focal.

Hexagon controls who occupies its Primary and Backup Focal appointments.
Original Founding Maintainers remain eligible to participate as maintainers if
they change employers or Hexagon changes its appointments.

Founder status is permanent historical attribution. Continued operational
access and decision authority are governance roles rather than property
rights. A comprehensive removal policy is not yet established.

## 3. Routine decisions

Routine technical and administrative decisions are made through consensus
among the participating Founding Maintainers. Discussion should be public
whenever practical.

Founding Maintainers may independently commit, merge, and perform routine
release work without mandatory review from another maintainer. This autonomy
does not override repository protections, security controls, employer
obligations, or the rules for major decisions.

Contributions from outside the Founding Maintainers require review and
approval by at least one Founding Maintainer with appropriate technical
knowledge.

## 4. Major decisions

Major decisions require explicit agreement between the Project Founder and
Lead Architect and the Hexagon Primary Focal. The Backup Focal acts for the
Primary Focal only when delegated or when the Primary Focal is unavailable.
The Backup Focal is not a second Hexagon vote.

Major decisions include:

- amending the core governance model;
- changing the project's license before a Hexagon stewardship transition;
- transferring control of the organization or material project assets;
- approving an incompatible or breaking public API change;
- making a formal compatibility, endorsement, or product representation on
  behalf of Hexagon; and
- materially changing the mission or proprietary boundary.

Breaking changes to the gRPC or Protocol Buffers API also require a documented
migration path.

## 5. Hexagon-reserved authority

Hexagon has final review authority only for matters involving:

- Hexagon trademarks, logos, and branding;
- Hexagon proprietary technology and confidential information;
- representations about Hexagon licensing;
- claims of official compatibility, certification, endorsement, or support;
  and
- disclosure and coordination of vulnerabilities that may affect
  SpatialAnalyzer or other Hexagon products.

This reserved authority does not extend to unrelated routine project
decisions. It also does not authorize project maintainers to bind Hexagon.

## 6. Delegation and absence

The Project Founder and Lead Architect or the Hexagon Primary Focal may
temporarily delegate decision authority. A material delegation should be
recorded in a durable private or public project channel, state its scope, and
state when it ends.

The Backup Focal may exercise the Primary Focal's authority during an
unavailability. If practicable, the Primary Focal should state the delegation
in advance.

## 7. Transparency and records

Roadmaps, architectural decisions, governance proposals, and decision
outcomes should be public by default. GitHub issues, discussions, pull
requests, and repository documents are preferred durable records.

Security reports, personnel matters, credentials, confidential corporate
information, and legally sensitive discussions may be handled privately. The
non-sensitive outcome should be recorded publicly when doing so is lawful and
appropriate.

## 8. Conflicts and deadlock

Participants should disclose a material conflict of interest and recuse
themselves when they cannot make a decision in the project's interest.
Employment alone is not treated as a disqualifying conflict; the project's
founding model expressly includes employer-associated participants.

The formal process for resolving a deadlock is not yet established. Until it
is, the Project Founder and Lead Architect and Hexagon Primary Focal will:

1. write down the decision, options, and disagreement;
2. seek relevant technical or organizational input;
3. pause irreversible action when practical; and
4. agree on an ad hoc resolution path.

Hexagon's reserved authority and pre-authorized stewardship right are not
changed by this temporary deadlock procedure.

## 9. Amendments

While the founding model remains in effect, material amendments require the
major-decision approval described above. Minor corrections and clarifications
may be merged by a Founding Maintainer when they do not change decision rights
or institutional commitments.
