# SCL-1.0-Reciprocal

Steven Compton Libraries — Reciprocal Open Source License v1.0  
(Scoped Reciprocal Open-Source License)

The **SCL-1.0-Reciprocal** license defines a reciprocal open-source legal
framework that preserves open use while requiring source disclosure for
forks, reimplementations, and works that replicate the core functional
behavior of the licensed Software.

The license protects against closed-source functional cloning without
imposing open-source obligations on larger products that merely use or
embed the Software.

This document outlines purpose, boundaries, and intended usage.

---

## Purpose

SCL-1.0-Reciprocal targets projects that seek open collaboration and reuse
while preventing closed-source forks or functional substitutes that
undermine shared development.

Projects select this license when they want:

- open use and integration across products and platforms  
- protection against closed-source reimplementations  
- reciprocity limited to functionally equivalent works  
- freedom to embed the Software in larger proprietary systems  
- clear attribution and origin integrity  
- trademark and identity protection  
- compatibility with SPDX, SBOMs, and automated tooling  

The license balances openness with structural reciprocity, preserving
community benefit without product-level contagion.

---

## Core Concepts

### **Scoped Reciprocity Model**

SCL-1.0-Reciprocal requires source-code disclosure only when a work:

- forks the Software, or  
- modifies the Software, or  
- reimplements or mimics the core functional behavior of the Software  

Reciprocity applies **only** to the component or system that performs the
same functional role as the original Software.

Larger products, platforms, or services that merely use, link to, embed,
or depend on the Software do not inherit open-source obligations.

---

### **Functional Boundary Protection**

The license draws a clear boundary between:

- **functional equivalents**, which must remain open, and  
- **dependent systems**, which may remain proprietary  

This prevents clean-room cloning, closed-source drop-in replacements, or
behaviorally equivalent substitutes from bypassing reciprocity through
architectural indirection or modular separation.

At the same time, the license preserves freedom to innovate, compete, and
build proprietary systems around the Software.

---

### **Attribution and Origin Integrity**

All distributions preserve attribution to the Author.

Attribution must remain:

- accurate  
- reasonably discoverable  
- accessible through ordinary use  

Attribution communicates authorship only and never implies endorsement,
certification, sponsorship, or affiliation.

This ensures long-term clarity of origin even as the Software evolves
through forks, extensions, or reimplementations.

---

### **Identity and Representation Protection**

SCL-1.0-Reciprocal protects against:

- brand impersonation  
- misleading project naming  
- deceptive marketing or metadata  
- confusing claims of official status  
- unqualified claims of behavioral equivalence  

Forks and reciprocal works must adopt distinct naming and branding that
avoid confusion with the original Software.

Claims of compatibility, equivalence, or replacement require clear
non-affiliation disclosure.

---

## Developer Expectations

Developers using this license:

- include the full license text with distributions  
- preserve original attribution  
- clearly mark modified versions  
- open-source any fork or functional equivalent under the same license  
- adopt distinct branding for forks or reciprocal works  
- avoid representations suggesting official status or endorsement  
- qualify claims of compatibility or behavioral similarity  

The license permits commercial use, proprietary integration, and closed
products, provided core functional reimplementations remain open.

---

## SPDX Integration

**SPDX Identifier:** `SCL-1.0-Reciprocal`

Projects using this license include the identifier within:

- package manifests  
- SBOM files  
- SPDX documents  
- license scanners  
- compliance tooling  

This enables automated license detection and ecosystem compatibility.

---

## Folder Contents

```text
SCL-1.0-Reciprocal/
│
├── SCL-1.0-Reciprocal.txt     # Canonical license text
└── README.md                  # This overview document
