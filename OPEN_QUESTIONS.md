# Open Governance Questions

This register makes incomplete policy visible. An unresolved item is not
permission to act without judgment; maintainers should use the existing
consensus process and avoid irreversible commitments when practical.

## Accepted Briosa implementation constraints

The following technical mechanics are accepted Briosa architecture. They
constrain implementations but do not settle the release and support policies
listed later in this register.

- Public MP contracts use exact-SpatialAnalyzer-target protobuf packages. One
  Briosa distribution supports one exact target, and a later target is a
  complete independently reviewed snapshot; matching shapes do not imply
  compatibility or permit nearest-version fallback. See
  [Briosa ADR 0005](https://github.com/spatialanalyzer/briosa/blob/main/docs/architecture/0005-exact-sa-target-protocols.md).
- Configured target identity, the SDK engine/type library selected by COM
  registration, and the connected SpatialAnalyzer application version are
  distinct facts. A verified mismatch fails closed, while unavailable runtime
  evidence remains distinguishable from operator attestation. See
  [Briosa ADR 0017](https://github.com/spatialanalyzer/briosa/blob/main/docs/architecture/0017-execution-channel-readiness.md)
  and [briosa#70](https://github.com/spatialanalyzer/briosa/issues/70).
- Briosa semantic version, exact SpatialAnalyzer target, command-catalog
  identity, protocol-artifact identity, and language-client package version are
  independent coordinates. Clients pin and verify a reproducible protocol
  artifact instead of copying shared semantics. See
  [Briosa ADR 0020](https://github.com/spatialanalyzer/briosa/blob/main/docs/architecture/0020-protocol-artifacts-and-client-conformance.md)
  and [briosa#94](https://github.com/spatialanalyzer/briosa/issues/94).

## Institutional and legal

- What is the final form of the relationship among the independent project,
  Hexagon, and the founders' employers?
- What exact Hexagon legal entity owns the SpatialAnalyzer and New River
  Kinematics marks, and what attribution language has Hexagon approved?
- What public terminology may be used for Hexagon's endorsement or
  sponsorship?
- Who owns the Briosa name, and should a trademark application be filed?
- What written permissions govern Hexagon logos and product branding?
- Will the project use a DCO, a CLA, another provenance process, or ordinary
  Apache-2.0 inbound licensing?
- Is written confirmation needed for redistribution of each category of
  generated COM interface artifact?

## Leadership and decisions

- What permanent process resolves a deadlock?
- How are non-founding maintainers nominated and approved?
- When does a maintainer become inactive or emeritus?
- What process governs resignation, removal, or emergency suspension?
- How is permanent Lead Architect succession handled after an interim
  appointment?
- What governance model should replace the founding model as the community
  grows?

## Community

- Which formal code of conduct and enforcement process, if any, should be
  adopted?
- How will confidential conduct reports be received and adjudicated?
- Under what conditions may a community-created language client become an
  official organization project?
- What response-time expectations, if any, should maintainers publish?
- Which channels are official for support and community discussion?

## Releases and compatibility

- What release-governance relationship should apply among Briosa semantic
  versions, command-catalog revisions, protocol artifacts, and independently
  versioned language clients?
- Which SpatialAnalyzer releases will initially be supported?
- How long will each Briosa/SpatialAnalyzer pairing receive fixes?
- Which server and language-client releases should be coordinated, despite
  retaining independent version identities?
- What release cadence, support window, and long-term-support policy will
  apply?
- What deprecation and migration policy should apply when support for an exact
  SpatialAnalyzer target ends?
- What automated conformance testing is required before claiming
  compatibility?

## Security and operations

- What acknowledgment and remediation targets should apply to vulnerability
  reports?
- Which maintainers should have organization-wide security-manager access?
- What is the official private fallback contact if GitHub private
  vulnerability reporting is unavailable?
- What incident-response and credential-rotation procedures are required?

## Funding and assets

- Will Boeing, Hexagon, a fiscal host, or another sponsor fund recurring
  services?
- Should the project form or join a legal entity?
- How should cash sponsorships, reimbursements, taxes, and financial
  reporting be handled?
- What spending threshold should require joint approval?
- Which critical services require a second administrator, and by what date?

## Review

The Founding Maintainers should review this register periodically and convert
settled answers into the relevant policy document. No fixed review interval
has yet been adopted.
