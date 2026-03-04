---
title: "QSGW: Conceptual Introduction"
date: 2026-03-04
tags: [QSGW, GW, Electronic Structure]
---

This is a short conceptual note on **quasiparticle self-consistent GW (QSGW)**.

## Big picture
- DFT gives a practical ground-state starting point, but quasiparticle energies (band gaps, band positions) can be inaccurate.
- GW introduces a **self-energy** Σ that improves quasiparticle energies using many-body perturbation theory.
- QSGW makes the *starting point itself* self-consistent by updating an effective one-particle Hamiltonian until the quasiparticle picture is stable.

## A useful mental model
Think of QSGW as *replacing the DFT exchange-correlation potential* with a better “effective” potential derived from Σ, then repeating until it no longer changes much.

## Why it helps
- Less dependence on the initial DFT functional
- Often improves band gaps and band ordering
- Useful for materials where standard DFT is too optimistic (especially gaps)

(You can expand this note later with equations, examples, and references.)
