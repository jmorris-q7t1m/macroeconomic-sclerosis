# The Stagnation-by-Clogging Regime: Computational Appendix
[![DOI](https://zenodo.org/badge/1465084175.svg)](https://doi.org/10.5281/zenodo.24389991)

> **Citation:** 
> Morris, J. (2026). The Stagnation-by-Clogging Regime: A Multi-Scale Framework of Macroeconomic Sclerosis (Version v1.1). Zenodo. [https://doi.org/10.5281/zenodo.24263451]

## Overview
This repository contains the executable computational appendix for the 2026 monograph *The Stagnation-by-Clogging Regime*. 

Standard macroeconomic frameworks assume that advanced economies operate near dynamic equilibrium, where aggregate growth corresponds to robust internal circulation. This repository provides simulation and diagnostic code demonstrating how a macroeconomy can endogenously freeze—exhibiting unit-root labor hysteresis, singular descriptor networks, and extreme markup entropy—while headline GDP and top-level asset metrics continue to expand.

By coupling Aubin Viability Theory and non-fungible resource thermodynamics with Variable Precision Rough Set (VPRS) logic, these notebooks map decentralized micro-level link pruning (`DROP(u)`) directly onto macroeconomic supply-network percolation and stealth recessionary states.

## Repository Contents

The codebase is consolidated into a single Jupyter/Google Colab Notebook (`stagnation_regime_simulations.ipynb`), structured into two primary executable sections:

### 1. Micro-Relational Depletion & Top-Down Network Percolation (Laws 1 & 2)
Simulates the endogenous micro-foundations of the holding-tank economy:
* **Thermodynamic Viability Collapse:** Models bounded agents exhausting a non-fungible resource vector $R_u = \{t, m, e, a\}$ (time, money, neuro-energy, action) under uncompensated entropy drift ($dS/dt > 0$). Demonstrates finite-time exit outside the Aubin viability kernel.
* **Competing-Risks Hazard Escalation:** Calculates bilateral hazard rates $\lambda_{d,u}(t)$ driving unilateral link deletion (`DROP(u)`).
* **Supply-Network Percolation:** Maps micro-pruning to the macro-network using an Elliott-Golub-Leduc fixed-point map, proving that localized frictions trigger discontinuous systemic collapse and push Leontief spectral radii toward unity ($\rho(A) \to 1$).

### 2. VPRS / DTRS Stealth Recession Empirical Classifier
A live empirical pipeline diagnosing the 2025-2026 U.S. macroeconomic divergence:
* **Automated FRED API Ingestion:** Pulls active macroeconomic state vectors covering classical output (Real GDP), labor slack (Unemployment), labor fluidity (JOLTS Hires), structural housing tolls (Case-Shiller HPI), and throughput buffers (Real Median Weekly Earnings).
* **Rough Set Discretization:** Applies Variable Precision Rough Set (VPRS) attribute reducts to classify the economy's discrete topological state.
* **The Stealth Recession Divergence:** Visually proves how classical NBER optical illusions (positive GDP, low headline unemployment) mask the internal circulatory freeze characterizing the stagnation-by-clogging regime.

## Getting Started / How to Run

The notebook is designed to be run directly in the browser via Google Colab with zero local environment configuration.

1. Click the **Open in Colab** badge at the top of the notebook.
2. **FRED API Key Required:** To run the empirical classifier (Section 2), you need a free API key from the Federal Reserve Bank of St. Louis (FRED). 
   * Get an API key here: [FRED API Keys](https://fred.account.stlouisfed.org/apikeys)
   * In Colab, either add your key to the built-in Secrets manager under the name `FRED_key`, or paste it into the designated variable in the cell.
3. Select **Runtime -> Run all** to execute the micro-simulations and pull the live empirical data.

## Theoretical Scaffolding (Monograph Mapping)
* **Paper I & IV (Macro-Empirical):** Labor hoarding, occupational licensing barriers, spatial mortgage lock-in, and household balance-sheet bifurcation.
* **Paper II (Top-Down Algebra):** Leontief-Ghosh spectral fragility, singular capital matrices ($\det(B)=0$), and VPRS diagnostic rule-induction.
* **Paper III (Micro-Axioms):** Non-substitutable resources, competing-risks hazard rates, and positional rent dissipation ($P_u \notin R_u$).
* **Paper V (Closure):** The multi-scale cross-layer operators connecting localized viability breaches to macroscopic network clogging.

## License
This project is licensed under the **Apache License 2.0**. See the [LICENSE](LICENSE) file for details.
