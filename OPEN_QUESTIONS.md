# Open Governance Questions

This register makes incomplete policy visible. An unresolved item is not
permission to act without judgment; maintainers should use the existing
consensus process and avoid irreversible commitments when practical.

## Accepted Briosa implementation constraints

The following technical mechanics are accepted Briosa architecture. They
constrain implementations but do not settle the release and support policies
listed later in this register.

- Public MP contracts use the protobuf package `briosa` for every exact
  SpatialAnalyzer target, with release-neutral service, message, and field
  names. Exact SpatialAnalyzer releases instead identify products, artifacts,
  packages, and runtime compatibility gates. Each target is a complete,
  isolated product validated independently against its exact release, and one
  running server is locked to one release; matching public names do not imply
  wire or behavioral compatibility or permit nearest-version fallback. See
  [Briosa operation and protocol model](https://github.com/spatialanalyzer/briosa/blob/main/docs/architecture/operation-and-protocol-model.md)
  and
  [exact-target product model](https://github.com/spatialanalyzer/briosa/blob/main/docs/architecture/exact-target-product-model.md).
- The exact SpatialAnalyzer release configured by the built target, the
  activated SDK engine/type library version, and the connected SpatialAnalyzer
  application version are distinct claims. Runtime evidence takes precedence;
  when it is unavailable, an operator may attest a claim with an explicit
  version and a non-sensitive evidence reference, but attestation cannot mask
  a runtime mismatch. Missing or mismatched identity fails closed. MP
  admission also requires a bounded execution-channel probe for the current
  worker generation; a successful `ConnectEx` alone is not readiness. An
  authoritative connected-application version probe remains provisional
  pending vendor guidance. See
  [Briosa runtime boundary and lifecycle](https://github.com/spatialanalyzer/briosa/blob/main/docs/architecture/runtime-boundary-and-lifecycle.md)
  and [briosa#70](https://github.com/spatialanalyzer/briosa/issues/70).
- Briosa semantic version, exact SpatialAnalyzer target, Windows runtime
  architecture, behavioral compatibility major and revision, protocol artifact
  snapshot, and language-client package version are independent coordinates.
  First-party clients are published per exact target and lock one reviewed
  protocol artifact for reproducible generation; contract-aware clients then
  validate the selected server's exact target and behavioral compatibility, so
  a compatible server need not match that artifact's release. Shared semantics
  stay in Briosa; clients do not redefine them. See
  [Briosa exact-target product model](https://github.com/spatialanalyzer/briosa/blob/main/docs/architecture/exact-target-product-model.md)
  and
  [client behavioral contract](https://github.com/spatialanalyzer/briosa/blob/main/docs/architecture/client-library-behavioral-contract.md).

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
  versions, behavioral compatibility majors and revisions, protocol artifacts,
  and independently versioned language clients?
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
