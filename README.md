[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19087378.svg)](https://doi.org/10.5281/zenodo.19087378)

# RFEP Framework

**The Renormalized Free-Energy Principle (RFEP): A Unified Mathematical Framework for Structural Bottleneck Resolution**

Version 1.6 -- with Pattern A Falsifiability Criterion

## Overview

The RFEP framework provides a unified mathematical bridge between Functional Stability Theory (FST) and domain-specific proofs. It formalizes how renormalized energy functionals detect and resolve structural bottlenecks across mathematics, physics, and computer science.

This repository contains both the English and German versions of the framework paper.

## Files

- `FST_Unified_Renormalized_Energy_Framework.tex` -- English version
- `FST_Unified_Renormalized_Energy_Framework_DE.tex` -- German version

## Zenodo

- **Current Version (v1.6):** [10.5281/zenodo.19106213](https://doi.org/10.5281/zenodo.19106213)
- **Concept DOI (all versions):** [10.5281/zenodo.19036190](https://doi.org/10.5281/zenodo.19036190)

## Domain Proof Papers -- Current Status

| Paper | Zenodo | Status | Open Problem | Next Step |
|-------|--------|--------|------------|------------------|
| **Turbulence** | [v1.3](https://doi.org/10.5281/zenodo.19056813) | Journal-ready | DFC1 empirical (only input) | Figures + falsification protocol |
| **Dark Energy** | [v1.6](https://doi.org/10.5281/zenodo.19036235) | Framework Note | Hu-Sawicki parameters quantitatively open | MCMC fit against DESI+Planck+Cassini |
| **Yang-Mills** | [v2.1](https://doi.org/10.5281/zenodo.19087433) | Conditional | Analytical proof of lambda < 0 | Doeblin minorisation programme |
| **Navier-Stokes** | [v2.1](https://doi.org/10.5281/zenodo.19087449) | Conditional | Assumption G2 (projection regularity) | Independent geometric verification |
| **NS Log-Distance** | [v1.3](https://doi.org/10.5281/zenodo.19056807) | Proof of Life verified | TLL for 3D NS analytically open | Kuramoto-Sivashinsky / reaction-diffusion |
| **BSD** | [v1.1](https://doi.org/10.5281/zenodo.19087443) | Reformulation | Higher Gross-Zagier (rank >= 2) | Rank 2-4 numerics, conditional labelling |
| **Hodge** | [v1.1](https://doi.org/10.5281/zenodo.19087439) | No-Go Theorem | = Deligne's question (1982) | Prismatic cohomology / AP4 |
| **P vs NP** | [v1.2](https://doi.org/10.5281/zenodo.19056809) | Reformulation | Uniformity Bridge | Instance compression formalisation |

## Proof Architecture

```
                    Framework (Pattern A)
                    +-- DS1-DS3 (Dissipative Selection)
                    +-- Second-Order Resolvent Dominance
                         |
          +--------------+--------------+
          |              |              |
     PROVEN        CONDITIONAL        OPEN
     (rigorous)   (reduced to       (= open
                  threshold axiom)   research)
          |              |              |
         TU:            YM:           BSD:
      DFC => NL'    Doeblin a > 0   Rank >= 2
      (journal)     (Kingman l < 0)  Gross-Zagier
                        |
         DE:           NS:          Hodge:
      Screening    G2 (projection)  Deligne's
      (validated)  G3 (Gronwall)    question
                        |
        NS-LDI:       PvNP:
      TLL + LDI     Uniformity
      (Lorenz OK)    Bridge
```

## Changelog

### v1.6
- Pattern A falsifiability criterion (rem:pattern-a-falsifiability)
- Three necessary conditions PA1-PA3 for Pattern A instances
- Explicit falsification criterion via first-order resolution

### v1.5
- Theorem (Dissipative Selection Principle DS1-DS3) as formal meta-theorem
- Pattern B (Flow Selection) defined for Dark Energy instantiation
- DS3 failure examples (translation escape, bubbling)
- DS genealogy remark (Sandier-Serfaty, MRS, AGS)
- Pattern A table extended with Hodge, BSD, P-vs-NP entries

### v1.4
- 5 systematic review cycles (score: 6.5 -> 9.4)

## Companion Papers (Concept DOIs)

| Paper | Concept DOI |
|-------|-------------|
| Yang-Mills Mass Gap | [10.5281/zenodo.19087433](https://doi.org/10.5281/zenodo.19087433) |
| Navier-Stokes Skeleton | [10.5281/zenodo.19087449](https://doi.org/10.5281/zenodo.19087449) |
| Navier-Stokes Log-Distance Integrability | [10.5281/zenodo.19056807](https://doi.org/10.5281/zenodo.19056807) |
| Turbulence | [10.5281/zenodo.19056813](https://doi.org/10.5281/zenodo.19056813) |
| Dark Energy | [10.5281/zenodo.19036235](https://doi.org/10.5281/zenodo.19036235) |
| Hodge Conjecture | [10.5281/zenodo.19087439](https://doi.org/10.5281/zenodo.19087439) |
| BSD Conjecture | [10.5281/zenodo.19087443](https://doi.org/10.5281/zenodo.19087443) |
| P vs NP | [10.5281/zenodo.19056809](https://doi.org/10.5281/zenodo.19056809) |


## Related Repositories

- [functional-stability-theory](https://github.com/research-line/functional-stability-theory) -- FST programme (main repository)
- [rh-even-dominance](https://github.com/research-line/rh-even-dominance) -- Riemann Hypothesis proofs
- [crm-cosmology](https://github.com/research-line/crm-cosmology) -- Cosmic Recursion Model

## Author

Lukas Geiger -- ORCID: [0009-0005-7296-1534](https://orcid.org/0009-0005-7296-1534)

## License

This work is licensed under [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/).
