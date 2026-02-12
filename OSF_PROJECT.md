# OSF Project: VDAC1 as the Mitochondrial Decision Gate

**Category**: Preprint / Open Data
**License**: CC BY 4.0
**DOI**: (pending OSF registration)

## Project Title

VDAC1 as the Mitochondrial Decision Gate: A Unifying Framework for Cannabidiol's Paradoxical Effects

## Contributors

- **Anthony J. Vasquez Sr.** — Delaware Valley University (Horticulture / Cannabis Pharmacology), Bucks County Community College (Information Technology). Corresponding author.
- **Faculty Advisor**: Professor Carla D. Garzon, PhD
- **AI Systems**: Claude Opus 4.6 (Anthropic), Gemini 2.5 Pro (Google DeepMind), Grok 4.1 (xAI), DeepSeek-Chat (DeepSeek), Mistral Large (Mistral AI). Full AI disclosure in manuscript Section 7.

## Abstract

Cannabidiol (CBD) exhibits paradoxical pharmacology: neuroprotection at low micromolar concentrations, yet selective cytotoxicity against tumor cells at higher concentrations. This paper proposes that VDAC1 (voltage-dependent anion channel 1) on the outer mitochondrial membrane functions as the decision gate routing CBD's effects toward protection or destruction based on pre-existing mitochondrial state.

Three convergent lines of evidence are presented: (1) systematic literature review of ~70 primary sources identifying VDAC1 as the pharmacological choke point, (2) six independent runs of an AI-driven evolutionary debate protocol (IRIS Gate Evo) converging on the same cofactor threshold equation, and (3) a novel chronopharmacology hypothesis predicting GSK3-beta/HK-II/VDAC1 cycling creates time-of-day-dependent therapeutic windows.

Citation integrity analysis revealed 4/7 AI-generated citations in the original student paper contained metadata errors despite accurate underlying science. All citations in this manuscript are PubMed-verified.

## Tags

cannabidiol, VDAC1, mitochondrial pharmacology, paradoxical drug effects, hexokinase-II, chronopharmacology, AI-augmented research, precision cannabinoid medicine, multi-model convergence, cofactor equation

## Component Structure

```
/
├── VDAC1_Mitochondrial_Decision_Gate.pdf    # Preprint manuscript (Feb 2026)
├── CITATION_INTEGRITY.md                     # Citation verification audit
├── OSF_PROJECT.md                            # This file
├── README.md                                 # Repository overview
│
├── gold/                                     # Extracted novel hypotheses
│   ├── circadian_vdac1_chronopharmacology.md # GSK3β/HK-II chronopharmacology model
│   ├── cbd_two_pathway_model.md              # CBD two-pathway via VDAC1
│   ├── lithium_two_pathway_model.md          # Lithium two-pathway via GSK-3β
│   ├── thc_two_pathway_model.md              # THC two-pathway via CB1 occupancy
│   └── mitochondrial_unification.md          # Cross-domain unification attempt
│
├── runs/                                     # Raw IRIS Gate Evo run data
│   ├── evo_20260210_222428_pharmacology/     # CBD/VDAC1 — S3 PASSED
│   ├── evo_20260210_224206_pharmacology/     # CBD/VDAC1 rerun — S3 PASSED
│   ├── evo_20260210_231236_pharmacology/     # Lithium — S3 PASSED
│   ├── evo_20260210_232635_neuroscience/     # Mitochondrial unification — S3 FAIL
│   ├── evo_20260210_232904_pharmacology/     # Lithium retry — S3 FAIL
│   ├── evo_20260210_235609_pharmacology/     # Lithium retry — S3 FAIL
│   ├── evo_20260211_024747_pharmacology/     # THC wellbeing — S3 FAIL (gold)
│   ├── evo_20260211_024750_neuroscience/     # THC neuroprotection — S3 FAIL (gold)
│   ├── evo_20260211_201329_pharmacology+bioelectric/  # Circadian CBD/VDAC1 — S3 FAIL (gold)
│   └── evo_20260212_032819_pharmacology/     # VDAC1 cofactor landscape — S3 FAIL (gold)
│
├── analysis/                                 # Cross-run convergence analysis
│   └── structural_isomorphism.md             # CBD/Lithium/THC pattern discovery
│
└── docs/                                     # Methodology notes, community posts
```

## Key Findings

### 1. The Cofactor Threshold Equation

Five of six independent IRIS Gate Evo runs converged on the same mathematical relationship:

```
Threshold = Kd x (1 + [HK-II]/Ki) x (Bcl-xL/Bax) x (1 + [tubulin]/Ki)
```

This predicts >10x higher cytotoxic thresholds in healthy neurons (TI > 10) versus cancer cells (TI < 5), explaining CBD's selectivity without invoking receptor specificity.

### 2. Structural Isomorphism

Three molecules independently produced the same two-pathway pattern:
- **CBD**: dose picks pathway via VDAC1 cofactor occupancy
- **Lithium**: dose picks pathway via GSK-3-beta inhibition depth
- **THC**: dose picks pathway via CB1 receptor occupancy fraction

### 3. Chronopharmacology Hypothesis (Novel)

Circadian GSK3-beta/AKT cycling drives rhythmic HK-II dissociation from VDAC1, creating time-of-day-dependent vulnerability windows. Prediction: CBD cytotoxicity IC50 shifts with circadian phase — lower when GSK3-beta is active (morning), higher when AKT is active (evening).

### 4. Methodological Discovery: Consensus Can Be Wrong

The circadian run produced the first documented case where 3/5 AI models converged on a factually incorrect claim (VDAC1 gating polarity). A single-model claim (Claude) was correct. Convergence amplifies shared training biases.

## Testable Predictions

1. VDAC1 blockade (DIDS or VBIT-4) should abolish CBD's selective cytotoxicity while preserving TRPV1/5-HT1A neuroprotection
2. CBD dose-response curves in circadian-synchronized cells should show IC50 shift between CT6 and CT18
3. GSK3-beta inhibitor (CHIR-99021) should abolish the circadian IC50 shift
4. HK-II overexpression should raise the cytotoxic threshold in cancer cell lines
5. VDAC1 cofactor profiling should predict CBD response across cell types

## Methodology

IRIS Gate Evo dispatches the same compiled research question to five independent LLMs. Models never see each other's outputs. The system discovers convergence through semantic claim embedding (all-MiniLM-L6-v2) and complete-linkage clustering (cosine >= 0.70). Claims are classified by overlap count: TYPE 0 (5/5 models), TYPE 1 (3-4/5), TYPE 2 (2/5), TYPE 3 (singular).

Full pipeline documentation: https://github.com/templetwo/iris-gate-evo

## Links

- **GitHub (Findings)**: https://github.com/templetwo/iris-evo-findings
- **GitHub (Engine)**: https://github.com/templetwo/iris-gate-evo
- **Preprint PDF**: Included in this repository
- **Community**: r/GrassrootsResearch

## Citation

Vasquez, A. J. Sr. (2026). VDAC1 as the Mitochondrial Decision Gate: A Unifying Framework for Cannabidiol's Paradoxical Effects. Preprint. Temple of Two Research. https://github.com/templetwo/iris-evo-findings

## Ethics and Transparency

- All AI contributions are disclosed in the manuscript (Section 7)
- Citation integrity audit included (CITATION_INTEGRITY.md)
- All PMIDs verified against PubMed as of February 2026
- Raw computational data (IRIS Gate Evo runs) included for reproducibility
- No experimental animals or human subjects were involved
