# Operational Navigation Definition

**Architecture Version:** v1.0 (Draft)

---

# Purpose

This document defines the operational navigation architecture of the Research Entry Package.

Whereas the Navigation Architecture defines how visitors progressively understand the research program,

the Operational Navigation defines how this conceptual navigation is implemented through GitHub.

Accordingly, this document specifies repository transitions rather than conceptual explanations.

---

# Background

The Dialogue-Phase Reasoning repository contains multiple independent research assets.

Although these assets are individually organized, first-time visitors require an explicit navigation path connecting them.

The objective of the Operational Navigation is therefore to transform conceptual navigation into practical repository navigation.

---

# Design Principle

Operational Navigation should satisfy the following principles.

- Navigation should always move from lower cognitive load to higher cognitive load.
- Every navigation step should have a clearly defined purpose.
- Visitors should never encounter large collections of documents without contextual guidance.
- Repository navigation should support, rather than replace, conceptual understanding.

Navigation therefore functions as a projection mechanism connecting repository implementation with visitor understanding.

---

# Navigation Layers

The operational navigation follows the sequence below.

```text
Repository README
        │
        ▼
Research Entry Package
        │
        ▼
Research Program Abstract
        │
        ▼
Reading Path
        │
        ▼
Core Research Assets
        │
        ▼
Research Repository
```

This sequence represents the default navigation path for first-time visitors.

---

# Repository Transitions

The operational transitions are implemented through explicit GitHub links.

Typical transitions include:

Repository README

↓

Research Entry Package

↓

Research Program Abstract

↓

Reading Path

↓

Representative Papers

↓

Research Architecture

↓

Methodologies

↓

Governance

↓

Terminology

↓

Research Maps

The navigation should remain flexible.

Visitors may leave the recommended path whenever appropriate.

---

# Navigation Philosophy

Operational Navigation should never force readers into a rigid sequence.

Instead, each document should recommend the next logical destination.

Every page should answer two questions:

- Why am I reading this?
- Where should I go next?

Navigation therefore becomes continuous rather than hierarchical.

---

# Link Design Principles

Every document within the Research Entry Package should include:

- links to prerequisite documents (when appropriate);
- links to recommended next documents;
- links to representative research assets.

Navigation links should be concise and clearly distinguish:

- previous step;
- current position;
- recommended next step.

---

# Relationship to Navigation Architecture

Navigation Architecture describes visitor understanding.

Operational Navigation describes repository implementation.

These architectures are complementary.

Neither replaces the other.

One models cognition.

The other models repository interaction.

---

# Scope

This document defines navigation implementation only.

It does not define:

- repository organization;
- research architecture;
- methodology structure;
- theoretical relationships.

These remain independent architectural layers.

---

# Future Evolution

Future versions may include:

- audience-specific navigation;
- enterprise navigation;
- academic navigation;
- educational navigation;
- adaptive navigation based on repository evolution.

Operational Navigation should therefore remain extensible while preserving the same navigation principles.

---

# Version

Operational Navigation Definition v1.0 (Draft)
