# formalization

This repository is a Lean 4 workspace for AI-assisted formalization of major analysis and PDE texts, including:

- Evans — *Partial Differential Equations*
- Brezis — *Functional Analysis, Sobolev Spaces and Partial Differential Equations*

## Project layout

- `/Formalization/Evans.lean` — entry point for Evans-related developments
- `/Formalization/Brezis.lean` — entry point for Brezis-related developments
- `/Formalization/Sobolev.lean` — entry point for Sobolev-space developments

## Getting started

1. Install the Lean toolchain specified in `/lean-toolchain`.
2. Build the project with `lake build`.

As the library grows, new chapters, definitions, lemmas, and theorems should be added under the matching book module.
