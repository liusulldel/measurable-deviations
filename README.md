# Measurable Deviations

**A Comment on “The Converse Envelope Theorem”**  
Shuo Li Liu · Research draft · 25 October 2026

The paper studies the domain of shifted-payoff integrals, gives a sufficient measurable-profile repair, and separates several auxiliary counterexamples from the conclusions they do and do not affect.

## Files

- `measurable-deviations.pdf`: the paper, with all figures and tables in the appendices.
- `measurable-deviations.tex`: LaTeX source.
- `lean-supplement.zip`: Lean sources, pinned dependencies, a claim map, and verification records.

## Formal verification

The supplement contains 16 mathematical modules with 241 public theorem declarations. The recorded successful build uses Lean 4.30.0 and mathlib revision `c5ea00351c28e24afc9f0f84379aa41082b1188f`.

The formal sources match the historical build record exactly. The later prose and layout revisions do not constitute a fresh Lean build. The archive's README distinguishes the historical verification record from the current manuscript and gives reproduction instructions.

The formal scope covers the paper's numbered mathematical results and additional counterexamples. Bibliographic interpretation, proof-dependency maps, and assessments of economic importance are outside that scope.

## Scope of the objections

The undefined-integral example establishes a missing domain condition. The spike refutes an auxiliary implication; the main equivalence excludes it through its explicit absolute-continuity premise. The approximation counterexample identifies a defect in the published proof without refuting its final implementability conclusion. The information continuity repair proved here is restricted to binary states with prior one half and the stated payoff assumptions.

This is a working paper, not a claim of journal acceptance.
