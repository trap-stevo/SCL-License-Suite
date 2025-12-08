# SCL-1.0-Universal

Steven Compton Universal License v1.0  
(Source-Available, No Redistribution, No Reverse Engineering)

The **SCL-1.0-Universal** license shapes a wide-scope, source-available legal
framework for software, hardware, cloud, embedded platforms, and future
multi-environment systems.  
The license grants controlled dependency usage while blocking redistribution,
reverse engineering, and any replication of internal behavior.

This document outlines purpose, boundaries, and integration expectations.

---

## Purpose

SCL-1.0-Universal targets large ecosystems, multi-runtime environments, and
systems that require strong protection of internal logic, structures, and
architectural sequencing.  
Projects select this license when they need:

- strict IP protection  
- zero replication of behavior  
- high-level extensibility through dependency boundaries  
- system-wide integration freedom without source exposure  
- compatibility with enterprise-scale SBOM and SPDX tools  

---

## Core Concepts

### **Dependent System**

A Dependent System:

- links to the Package  
- integrates the Package  
- relies on the Package’s logic or behavior  
- runs the Package inside its architecture  

but never exposes, includes, or embeds Package code.

This construct covers:

- applications  
- services  
- runtimes  
- hardware or firmware integrations  
- cloud or edge systems  
- embedded devices  
- multi-platform frameworks  

### **Protection Layer**

SCL-1.0-Universal creates a protective layer around:

- source code  
- object code  
- design logic  
- structure  
- behavior  
- architectural flow  

No redistribution, no forking, no internal replication, no reverse
engineering, and no behavioral extraction.

---

## Developer Expectations

Developers using this license:

- reference the Package only through allowed integration paths  
- credit the dependency in documentation  
- introduce original functionality  
- avoid any feature that replicates the Package’s operational model  
- maintain compliance with all anti-redistribution rules  

---

## SPDX Integration

**SPDX Identifier:** `SCL-1.0-Universal`

Every package using this license inserts the identifier inside:

- package manifests  
- SBOM files  
- SPDX documents  
- open-source scanners  
- compliance dashboards  

---

## Folder Contents

````text
SCL-1.0-Universal/
│
├── SCL-1.0-Universal.txt      # Canonical license text
└── README.md                  # This overview document

