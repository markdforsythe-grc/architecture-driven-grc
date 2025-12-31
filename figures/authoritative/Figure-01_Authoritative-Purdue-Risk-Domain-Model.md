# Figure 01 — Authoritative Purdue Risk Domain Model

![Figure 01 — Authoritative Purdue Risk Domain Model](Figure-01_Authoritative-Purdue-Risk-Domain-Model.png)

## Purpose

This figure defines the authoritative Purdue-aligned risk domains used throughout the Architecture-Driven GRC Framework.

It establishes:
- Domain ordering
- Trust and consequence boundaries
- Directional risk and control flow
- The role of Level 3.5 as a mandatory mediation domain

## Key Concepts

- Risk flows downward toward physical consequence
- Controls flow upward to intercept and constrain risk
- Each Purdue level represents a distinct risk domain
- Level 3.5 (Operations DMZ) is not a passthrough layer

## Architectural Implication

Architectures that violate these domain boundaries introduce unmanaged risk propagation and non-linear increases in severity.

This figure is a canonical reference and must not be altered without framework review.
