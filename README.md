# IRIS Evo Findings

Curated experimental results from [IRIS Gate Evo](https://github.com/templetwo/iris-gate-evo) — a multi-LLM convergence protocol for scientific discovery.

Five independent AI models (Claude, Gemini, Grok, DeepSeek, Mistral) receive the same research question, respond independently, and the system finds convergence through semantic claim embedding. What survives is consensus science — falsifiable hypotheses with Monte Carlo power analysis.

## Preprint

**[VDAC1 as the Mitochondrial Decision Gate: A Unifying Framework for Cannabidiol's Paradoxical Effects](VDAC1_Mitochondrial_Decision_Gate.pdf)** — Vasquez Sr., A.J. (February 2026)

The paper proposes that VDAC1 on the outer mitochondrial membrane functions as the decision gate routing CBD's effects toward neuroprotection or cytotoxicity based on pre-existing mitochondrial state. It presents the cofactor threshold equation converged upon by six independent IRIS Gate Evo runs, a novel chronopharmacology hypothesis linking GSK3-beta cycling to time-of-day-dependent therapeutic windows, and a citation integrity analysis documenting AI hallucination patterns in scientific bibliographies.

See [OSF_PROJECT.md](OSF_PROJECT.md) for structured metadata and component descriptions.

See [CITATION_INTEGRITY.md](CITATION_INTEGRITY.md) for the full citation verification audit.

## Key Discovery: Structural Isomorphism

Three independent runs surfaced the **same pattern** across different molecules:

| Molecule | Gateway | Therapeutic Pathway | Pathological Pathway |
|----------|---------|--------------------|--------------------|
| **CBD** | VDAC1 conductance | Low ROS (healthy) → survival | High ROS (cancer) → apoptosis |
| **Lithium** | GSK-3β inhibition | <1mM → neuroprotective | >2mM → toxic |
| **THC** | CB1 occupancy | <30% → G-protein biased (wellbeing) | >30% → beta-arrestin (tolerance) |

**The pattern**: molecule is stress test, dose picks pathway, tissue determines outcome.

## Repository Structure

```
runs/           # Raw run data (per-stage JSON from each pipeline execution)
gold/           # Extracted insights from failed S3 runs (buried gold)
analysis/       # Cross-run pattern analysis and structural comparisons
docs/           # Write-ups, community posts, methodology notes
```

## Runs Index

| Session ID | Question | Domain | Outcome | Key Finding |
|-----------|----------|--------|---------|-------------|
| `evo_20260210_222428` | CBD/VDAC1 cytotoxicity | pharmacology | S3 PASSED | Two-pathway model validated |
| `evo_20260210_224206` | CBD/VDAC1 (rerun) | pharmacology | S3 PASSED | Reproducible convergence |
| `evo_20260210_231236` | Lithium mood stabilization | pharmacology | S3 PASSED | GSK-3β two-pathway, d=0.85-1.17 |
| `evo_20260210_232635` | Mitochondrial unification | neuroscience | S3 FAILED | Genuine scientific disagreement |
| `evo_20260210_232904` | Lithium (retry) | pharmacology | S3 FAILED | LiteLLM errors cycle 2 |
| `evo_20260210_235609` | Lithium (retry) | pharmacology | S3 FAILED | Stochastic — convergence is probabilistic |
| `evo_20260211_024747` | THC sustained wellbeing | pharmacology | S3 FAILED (gold) | CB1 occupancy model, 2-AG synergy, HPA axis |
| `evo_20260211_024750` | THC aging neuroprotection | neuroscience | S3 FAILED (gold) | 5/5 TYPE 0 GABAergic disinhibition |
| `evo_20260211_201329` | Circadian CBD/VDAC1 | pharmacology+bioelectric | S3 FAILED (gold) | GSK3-beta chronopharmacology, TYPE 1 consensus error |
| `evo_20260212_032819` | VDAC1 cofactor landscape | pharmacology | S3 FAILED (gold) | Cofactor equation, f_free^4 cooperativity |

## THC Two-Pathway Model

Extracted from two S3-failed runs that independently converged on the same mechanistic framework:

**Core finding**: Low CB1 occupancy (<20-30%) engages G-protein biased signaling, avoiding beta-arrestin desensitization. This means low-dose THC supplements your endocannabinoid system rather than replacing it.

Key claims (multi-model convergence):
- **Kinetic crossover**: Tolerance is a phase transition at ~30% occupancy where internalization exceeds recycling (k_int > k_rec + k_syn)
- **2-AG synergy**: Low-dose THC adds to tonic 2-AG without displacement; high-dose saturates CB1 and upregulates MAGL
- **Biased agonism**: G-protein EC50 ~10nM vs beta-arrestin EC50 >100nM — bias factor ~3-5x
- **GABAergic disinhibition** (aging): 5/5 models agreed aged hippocampus has pathologically elevated GABA tone

Novel singulars (single-model, high potential):
- eCB-LTD potentiation at amygdala synapses (Gemini)
- HPA axis recalibration via PVN CB1 — 20-35% cortisol reduction (Claude)
- AMPA nanodomain clustering rescue in aged synapses (DeepSeek)

## Methodology

See the [IRIS Gate Evo repo](https://github.com/templetwo/iris-gate-evo) for full pipeline documentation.

**Core principle**: Independence produces better convergence than debate. Models never see each other's outputs. Agreement is discovered, not manufactured.

## Related Projects

- [IRIS Gate Evo](https://github.com/templetwo/iris-gate-evo) — The convergence engine
- [CBD Two-Pathway Model](https://github.com/templetwo/cbd-two-pathway-model) — First validated finding
- [Mass-Coherence Correspondence](https://github.com/templetwo/mass-coherence-correspondence) — Foundational theory

## License

Research findings shared under CC BY 4.0. Cite as: Temple of Two, IRIS Evo Findings, 2026.
