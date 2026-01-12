# SCL License Suite — Overview

The Steven Compton License Suite (SCL Suite) defines a modular, expandable
family of software licenses engineered for long-term evolution across
software, hardware, firmware, cloud platforms, embedded systems, and
multi-device ecosystems.

Each license within the suite establishes an independent permission model
without forcing a single policy across all use cases.
This structure supports:

- permissive open-source licenses
- restricted source-available licenses
- commercial and subscription-based licenses
- dual-licensing structures
- device-level and platform-level usage rules
- hybrid models for future technology stacks

The SCL Suite grows over time while each license preserves clear boundaries,
explicit rights, and well-defined limitations.

---------------------------------------------------------------------

# Current Licenses in the Suite

## 1. SCL-1.0-Open  
**SPDX Identifier:** SCL-1.0-Open

A permissive, open-source license designed for broad adoption while preserving
strong attribution, identity integrity, and protection against misleading
representation.

SCL-1.0-Open permits unrestricted use, modification, redistribution, and
commercial deployment, while enforcing:

- clear authorship attribution
- discoverable origin identification
- trademark and branding protection
- safeguards against confusing or deceptive representation
- patent grant with retaliation protection

Suitable for open libraries, frameworks, tools, and foundational components
intended for public reuse.

---------------------------------------------------------------------

## 2. SCL-1.0  
**SPDX Identifier:** SCL-1.0

A foundational dependency-usage license that restricts redistribution,
forking, and reverse engineering.

Designed for engines, SDKs, internal tools, and systems requiring strong
intellectual property protection while still allowing integration into
dependent systems.

---------------------------------------------------------------------

## 3. SCL-1.0-Universal  
**SPDX Identifier:** SCL-1.0-Universal

A broad-scope, source-available license supporting use across:

- software components
- hardware and firmware
- cloud and edge services
- embedded architectures
- multi-device and multi-runtime environments

The **Dependent System** construct enables wide integration while maintaining
strict anti-redistribution rules, behavioral protection, and structural
integrity.

---------------------------------------------------------------------

## 4. SCL-Enterprise-1.0  
**SPDX Identifier:** SCL-Enterprise-1.0

A commercial, subscription-backed license offering:

- expanded deployment allowances
- SLA-backed commitments
- controlled expansion of rights
- enterprise-approved legal terms
- dual-licensing or upgrade paths from other SCL licenses

Intended for regulated, large-scale, or mission-critical deployments.

---------------------------------------------------------------------

# Philosophy of the SCL Suite

The SCL Suite prioritizes:

- clarity in rights and responsibilities
- explicit boundaries between license models
- strong IP protection where required
- predictable structures for legal and compliance teams
- compatibility with SPDX, SBOMs, and automated tooling
- long-term stability for ecosystem adoption

The suite intentionally separates **permission models** rather than collapsing
them into a single license, allowing projects to select the appropriate level
of openness or restriction without ambiguity.

---------------------------------------------------------------------

# Future Expansion

Future licenses in the SCL Suite may include:

- additional permissive SCL variants
- hardware-specific or firmware-specific licenses
- time-gated or delayed-open licenses
- research and academic-use licenses
- internal-use corporate agreements
- hybrid licenses for emerging runtimes, AI systems, or novel hardware stacks

Each new license will remain independent and will not retroactively modify
existing licenses.

---------------------------------------------------------------------

# SPDX & Tooling Integration

Each license directory contains:

- canonical legal text (.txt or .md)
- a README.md describing intended usage and scope
- a fixed SPDX identifier for scanners and SBOM generators
- optional placeholder metadata that never alters legal meaning
- content prepared for SPDX License List submission

SPDX submission entry point:  
https://github.com/spdx/license-list-XML/issues/new/choose

---------------------------------------------------------------------

# License Directory Structure

SCL-License-Suite/
│
├── LICENSE-NAME-[VERSION]/
│   ├── LICENSE-NAME-[VERSION].txt
│   └── README.md
│
└── SCL-Suite-Overview.md

---------------------------------------------------------------------

# Versioning Strategy

The SCL Suite follows a clear versioning model:

- **Major versions** — structural or conceptual legal changes
- **Minor versions** — refined clauses or expanded definitions without
  changing intent
- **Patch versions** — wording clarifications or formatting improvements

Each license tracks its own version history.
Updates to one license never modify another license automatically.
