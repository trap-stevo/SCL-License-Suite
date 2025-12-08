# SCL License Suite — Overview

The Steven Compton License Suite (SCL Suite) defines a modular, expandable
family of licenses engineered for long-term evolution across software, hardware,
firmware, cloud platforms, embedded systems, and multi-device ecosystems.

Each license establishes its own permission model without forcing a single
policy over the entire suite.
This structure supports:

- permissive constructs
- restricted source-available constructs
- commercial and subscription constructs
- dual-licensing structures
- device-level and platform-level rules
- hybrid models for future technology stacks

The SCL Suite grows over time while each license preserves clear boundaries,
rights, and limitations.

---------------------------------------------------------------------

# Current Licenses in the Suite

## 1. SCL-1.0
SPDX Identifier: SCL-1.0

A foundational dependency-usage license that restricts redistribution,
forking, and reverse engineering. Suitable for engines, SDKs, internal tools,
and systems requiring strong IP protection.

---------------------------------------------------------------------

## 2. SCL-1.0-Universal
SPDX Identifier: SCL-1.0-Universal

A broad-scope license supporting:

- software components
- hardware and firmware
- cloud and edge services
- embedded architectures
- multi-device and multi-runtime environments

The “Dependent System” construct enables wide integration while maintaining
strict anti-redistribution rules and structural protection.

---------------------------------------------------------------------

## 3. SCL-Enterprise-1.0
SPDX Identifier: SCL-Enterprise-1.0

A commercial, subscription-backed license offering:

- deployment allowances
- SLA-backed commitments
- controlled expansion of rights
- enterprise-approved terms
- dual-licensing or upgrade paths

---------------------------------------------------------------------

# Philosophy of the SCL Suite

The suite focuses on:

- clarity in rights and responsibilities
- strong IP protection where required
- predictable structures for legal and compliance teams
- smooth expansion across new license families
- alignment with SPDX, SBOMs, and automated tooling
- stability for long-term ecosystem adoption

Future licenses may include:

- permissive SCL variants
- hardware-integration agreements
- time-gated open-after-N-years models
- research-focused licenses
- internal-use corporate agreements
- hybrid licenses for emerging runtimes or hardware stacks

---------------------------------------------------------------------

# SPDX & Tooling Integration

Each license folder contains:

- canonical .txt legal text
- README.md describing intended usage
- SPDX identifier for scanners and SBOM generators
- placeholder metadata that never alters legal meaning
- content prepared for SPDX License List submission

SPDX submission entry point:
https://github.com/spdx/license-list-XML/issues/new/choose

---------------------------------------------------------------------

# License Directory Structure

```txt
SCL-License-Suite/
│
├── LICENSE-NAME-[VERSION]/
│   ├── LICENSE-NAME-[VERSION].txt
│   └── README.md
│
└── SCL-Suite-Overview.md
```

---------------------------------------------------------------------

# Versioning Strategy

The SCL Suite follows:

- Major versions — structural or conceptual legal changes
- Minor versions — refined clauses or expanded definitions without shifting intent
- Patch versions — wording clarifications or formatting improvements

Each license tracks its own version history.
Updates in one license never modify another license automatically.
