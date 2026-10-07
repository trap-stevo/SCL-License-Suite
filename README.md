# SCL License Suite — Overview

The Steven Compton License Suite (SCL Suite) defines a modular, expandable
family of software licenses engineered for long-term evolution across
software, hardware, firmware, cloud platforms, embedded systems, and
multi-device ecosystems.

Each license within the suite establishes an independent permission model
without forcing a single policy across all use cases.
This structure supports:

- permissive open-source licenses
- reciprocal open-source licenses
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
**License Identifier:** SCL-1.0-Open

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

No obligation exists to publicly disclose modifications.

Suitable for open libraries, frameworks, tools, and foundational components
intended for maximum reuse and ecosystem adoption.

---------------------------------------------------------------------

## 2. SCL-1.0-Reciprocal  
**License Identifier:** SCL-1.0-Reciprocal

A reciprocal open-source license that preserves open use while requiring
source-code disclosure for works that replicate or reimplement the core
functional behavior of the licensed Software.

SCL-1.0-Reciprocal enforces reciprocity only at the level of functional
equivalence. Larger products, platforms, or systems that merely use or embed
the Software do not inherit open-source obligations.

The license enforces:

- mandatory open sourcing of forks and functional equivalents
- protection against closed-source reimplementations
- clear separation between reusable components and larger systems
- strong attribution and origin integrity
- trademark and identity protection
- patent grant with retaliation protection
- network-use disclosure for qualifying reciprocal works

Suitable for core engines, protocols, runtimes, and systems where functional
cloning should remain open without imposing product-level contagion.

---------------------------------------------------------------------

## 3. SCL-1.0  
**License Identifier:** SCL-1.0

A foundational dependency-usage license that restricts redistribution,
forking, and reverse engineering.

Designed for engines, SDKs, internal tools, and systems requiring strong
intellectual property protection while still allowing integration into
dependent systems.

---------------------------------------------------------------------

## 4. SCL-1.0-Universal  
**License Identifier:** SCL-1.0-Universal

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

## 5. SCL-1.1-Universal  
**License Identifier:** SCL-1.1-Universal

An updated source-available license for commercial and noncommercial use as
an integrated dependency in genuine applications, services, frameworks, SDKs,
plugins, and developer tools. It permits ordinary build transformations and
necessary integrated runtime distribution, while restricting standalone
redistribution, unauthorized modifications, public mirroring, and disguised
package republishing.

- [Canonical plain-text license](SCL-1.1-Universal/SCL-1.1-Universal.txt)
- [Markdown license](SCL-1.1-Universal/SCL-1.1-Universal.md)
- [Integration guide](SCL-1.1-Universal/README.md)

SCL-1.1-Universal does not retroactively replace SCL-1.0-Universal or alter
rights granted to previously distributed releases.

---------------------------------------------------------------------

## 6. SCL-Enterprise-1.0  
**License Identifier:** SCL-Enterprise-1.0

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
- compatibility with software bills of materials (SBOMs) and automated tooling
- long-term stability for ecosystem adoption

The suite intentionally separates **permission models** rather than collapsing
them into a single license, allowing projects to select the appropriate level
of openness or restriction without ambiguity.

---------------------------------------------------------------------

# Future Expansion

Future licenses in the SCL Suite may include:

- additional permissive or reciprocal SCL variants
- hardware-specific or firmware-specific licenses
- time-gated or delayed-open licenses
- research and academic-use licenses
- internal-use corporate agreements
- hybrid licenses for emerging runtimes, AI systems, or novel hardware stacks

Each new license will remain independent and will not retroactively modify
existing licenses.

---------------------------------------------------------------------

# License Metadata & Tooling Integration

Each included license has its own identifier and applicable legal text.
Use package-manager-supported custom-license metadata and include the full
applicable license with each Package release. An internal license identifier
does not by itself establish registration in any external license registry.

The repository currently contains canonical texts for SCL-1.0-Open,
SCL-1.0-Reciprocal, SCL-1.0-Universal, and SCL-1.1-Universal.
SCL-1.0 and SCL-Enterprise-1.0 remain documented suite models in this
overview; their canonical license files are not included in this archive.

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
