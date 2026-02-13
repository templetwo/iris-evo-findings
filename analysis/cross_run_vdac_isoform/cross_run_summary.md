# Cross-Run Convergence Report

**Generated**: 2026-02-13 18:09 UTC
**Runs analyzed**: 11
**Total claims**: 104
**Cross-matches found**: 3

## Runs

| Session | Domain | S3 | Claims |
|---------|--------|----|--------|
| evo_20260210_232904_pharmacology | pharmacology | FAIL | 13 |
| evo_20260210_235609_pharmacology | pharmacology | FAIL | 9 |
| evo_20260211_024747_pharmacology | pharmacology | FAIL | 9 |
| evo_20260211_024750_neuroscience | neuroscience | FAIL | 7 |
| evo_20260211_201329_pharmacology+bioelectric | pharmacology+bioelectric | FAIL | 10 |
| evo_20260212_032819_pharmacology | pharmacology | FAIL | 7 |
| evo_20260213_004656_consciousness | consciousness | FAIL | 10 |
| evo_20260213_022353_consciousness+chemistry | consciousness+chemistry | FAIL | 15 |
| evo_20260213_035958_pharmacology | pharmacology | PASS | 9 |
| evo_20260213_042930_pharmacology | pharmacology | PASS | 9 |
| evo_20260213_174104_pharmacology | pharmacology | FAIL | 6 |

## Cross-Validated Singulars

### CROSS-VALIDATED SINGULAR (cosine=0.7765)
- **Run A** (evo_20260210_232904_pharmacology, TYPE 3): Lithium neuroprotection at low dose (<0.5 mM) primarily via partial GSK3β inhibition (IC50 1-2 mM), stabilizing β-catenin, upregulating BDNF and autop
- **Run B** (evo_20260210_235609_pharmacology, TYPE 0): 2:** Neuroprotection at low dose is mediated primarily by indirect GSK-3β inhibition via Akt-Ser9 phosphorylation amplification, with effective EC50 ~

## Independent Replications

- **cosine=0.789** | evo_20260213_035958_pharmacology ↔ evo_20260213_042930_pharmacology
  A: 1:** *CBD is unlikely to reach VDAC1-saturating concentrations (≥11 µM) in healthy hepatocytes under standard oral dosin
  B: At 50mg/day oral CBD, steady-state hepatic [CBD] ~0.1-0.5μM (plasma 0.05-0.2μM × liver enrichment), VDAC occ <5%, ROS lo

## Cross-Promoted (TYPE 2 → validated)

- **cosine=0.7914** | evo_20260211_024747_pharmacology (T2) ↔ evo_20260211_024750_neuroscience (T0)
  A: 1:** Chronic low-dose THC (≤2.5 mg/day) improves wellbeing via *biphasic CB1 signaling*: G-protein activation (EC50 ~10 
  B: 1:** The biphasic (inverted-U) dose-response of THC occurs because low CB1 occupancy (<20%) preferentially engages Gi/o-

## Structural Patterns (Isomorphism)

- **two_pathway**: evo_20260210_232904_pharmacology, evo_20260212_032819_pharmacology
- **threshold_crossover**: evo_20260210_232904_pharmacology, evo_20260210_235609_pharmacology, evo_20260211_024747_pharmacology, evo_20260211_024750_neuroscience, evo_20260212_032819_pharmacology, evo_20260213_022353_consciousness+chemistry, evo_20260213_042930_pharmacology
- **dose_dependent**: evo_20260210_232904_pharmacology, evo_20260211_024747_pharmacology, evo_20260212_032819_pharmacology, evo_20260213_035958_pharmacology, evo_20260213_042930_pharmacology, evo_20260213_174104_pharmacology

## Cosine Distribution (cross-run pairs)

- Min: -0.1937
- Median: 0.2183
- Mean: 0.2221
- Max: 0.7914
- N pairs: 4882
