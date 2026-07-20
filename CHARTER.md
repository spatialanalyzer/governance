# Project Charter

## 1. Mission

The SpatialAnalyzer GitHub organization exists to develop and host
open-source tools, documentation, and examples related to the SpatialAnalyzer
product ecosystem.

Its initial project family is **Briosa**. Briosa aims to:

1. provide an open-source gRPC server that presents a clean interface to
   SpatialAnalyzer Measurement Plan and SDK capabilities;
2. provide thin, idiomatic client libraries for supported programming
   languages;
3. make integrations easier to build, test, and maintain; and
4. encourage collaboration across the manufacturing and metrology community.

Planned repositories include the Briosa server, protocol definitions,
language clients such as `briosa-dotnet`, `briosa-js`, and `briosa-py`,
documentation, example applications, and conformance or integration tests.

## 2. Current status

The organization is initially an independently administered open-source
effort founded by engineers associated with Boeing and Hexagon. Participation
by an individual does not, by itself, mean that the individual's employer
owns the project, has accepted liability for it, or is bound by a project
decision.

The project is being developed with support from Hexagon. This conservative
description should be used until Hexagon approves more specific public
language about endorsement or sponsorship.

The long-term institutional relationship among the project, Hexagon, and
other potential sponsors has not been fully established. Hexagon is
pre-authorized to assume stewardship as described in
[STEWARDSHIP.md](STEWARDSHIP.md).

## 3. Open-source commitment

The project begins under the Apache License 2.0. Each software repository must
include its own license file.

Existing Apache-2.0 grants are not withdrawn by a future governance or
stewardship change. Hexagon may determine the licensing policy for future
development after assuming stewardship, subject to applicable contributor
rights and agreements.

## 4. Product and license boundary

Briosa is an integration layer; it is not SpatialAnalyzer and does not include
or replace a SpatialAnalyzer license.

- SpatialAnalyzer, the SA SDK, and other closed-source Hexagon products are
  outside the project's open-source scope.
- Briosa may be downloaded and started without an active SpatialAnalyzer
  license, but it cannot perform its intended SpatialAnalyzer operations
  without access to a properly licensed and functioning SpatialAnalyzer
  installation.
- The project will not publish closed-source Hexagon code, documentation, or
  assets.
- Generated interface artifacts may be included only when the maintainers have
  confirmed that their generation and redistribution are authorized.
- Contributors must not submit confidential, export-controlled, employer-owned,
  or third-party material without authority to do so.

Which SpatialAnalyzer releases are supported will be documented by individual
Briosa releases. The initial support matrix is not yet established.

## 5. Independence and support

Community issues, discussions, and releases are project activities. They are
not a substitute for official Hexagon support, warranty, or product
commitments. Compatibility statements apply only to the configurations the
project expressly identifies as tested.

Software is provided under the warranty and liability terms of its applicable
open-source license.

## 6. Values

The project intends to favor:

- accurate representations of SpatialAnalyzer and tested compatibility;
- transparent technical and governance decisions;
- stable, language-appropriate public interfaces;
- respectful collaboration;
- protection of proprietary and security-sensitive information; and
- a practical path for participation by the broader manufacturing community.

Formal policies for several of these goals remain under development. See
[OPEN_QUESTIONS.md](OPEN_QUESTIONS.md).
