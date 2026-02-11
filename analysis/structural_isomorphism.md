# Structural Isomorphism Across Pharmacological Two-Pathway Models

**Date**: 2026-02-11
**Source**: Cross-run analysis of IRIS Gate Evo pipeline results

## The Pattern

Three independent IRIS Evo runs — different molecules, different questions, different domains — converged on the same abstract pattern:

**Every molecule is a stress test. Dose picks the pathway. Tissue determines outcome.**

## Evidence Table

| Property | CBD | Lithium | THC |
|----------|-----|---------|-----|
| **Gateway receptor/target** | VDAC1 (mitochondrial channel) | GSK-3beta (kinase) | CB1 (GPCR) |
| **Dose selector** | Concentration at mitochondria | Serum level | Daily dose / occupancy |
| **Therapeutic range** | Sub-IC50 | <1 mM | <2.5 mg/day (<30% occupancy) |
| **Pathological range** | Supra-IC50 | >2 mM | >10 mg/day (>30% occupancy) |
| **Pathway A (therapeutic)** | Mild depolarization, ROS signaling | Wnt pathway activation | G-protein biased signaling |
| **Pathway B (pathological)** | Massive depolarization, apoptosis | Renal toxicity | Beta-arrestin recruitment, tolerance |
| **Tissue discriminator** | Cancer (high basal ROS) vs healthy (low) | Brain vs kidney | Naive (intact CB1) vs tolerant (downregulated) |
| **S3 outcome** | PASSED (3 hypotheses) | PASSED (4 hypotheses, d=0.85-1.17) | FAILED (rich gold from 2 runs) |

## Why This Matters

This is not cherry-picking. The pipeline didn't know about this pattern. Five models were asked three unrelated questions and independently arrived at structurally equivalent answers. The isomorphism was discovered post-hoc by comparing results across runs.

This suggests the two-pathway model may be a **general organizing principle for pharmacology**: most small molecules interact with dose-dependent targets where the dose selects between beneficial and harmful downstream cascades, and the tissue context (pre-existing state) determines which cascade dominates.

## Predictions

If this isomorphism is real (not artifact), then:

1. **Other molecules should exhibit the same pattern** when run through IRIS Evo
2. The **gateway target** should always be identifiable (receptor, enzyme, channel)
3. The **dose selector** should be quantifiable with a crossover threshold
4. The **tissue discriminator** should explain inter-individual variation in drug response

## Next Tests

- **Psilocybin**: 5-HT2A occupancy — low (neuroplastic, default mode disruption) vs high (perceptual destabilization)?
- **Metformin**: AMPK activation — dose-dependent switch between metabolic benefit and lactic acidosis?
- **Aspirin**: COX inhibition — low-dose (cardioprotective, anti-platelet) vs high-dose (gastric erosion)?

These would either strengthen or falsify the isomorphism hypothesis.
