<!--[![Paper](https://img.shields.io/badge/paper-arXiv%3AXXXX.YYYYY-B31B1B.svg)](https://arxiv.org/abs/XXXX.YYYYY)-->
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10150018.svg)](https://doi.org/10.5281/zenodo.10150018)

# Effects of substrate corrugation during helium adsorption on graphene in the grand canonical ensemble

Gage Erwin, Adrian Del Maestro

<!--[arXiv:XXXX.YYYYY](https://arxiv.org/abs/XXXX.YYYYY)-->

### Abstract
Adsorption of ${}^4$He on graphene substrates has been a topic of great interest due to the intriguing effects of graphene corrugation on the manifestation of commensurate solid and exotic phases in low-dimensional systems. In this study, we employ worm algorithm quantum Monte Carlo to study helium adsorbed on a graphene substrate to explore corrugation effects in the grand canonical ensemble. We utilized a Szalewicz potential for helium-helium interactions and a summation of isotropic interactions between helium and carbon atoms to construct a helium-graphene potential. We implement different levels of approximation to achieve a smooth potential, three partially corrugated potentials, and a fully ab initio potential to test the effects of corrugation on the first and second layers. We demonstrate that the omission of corrugation within the helium-graphene potential could lead to finite-size effects in both the first and second layers. Thus, a fully corrugated potential should be used when simulating helium in this low-dimensional regime.

### Description
This repository includes links, code, scripts, and data to generate figures and reproduce results in the paper.

### Requirements
The data in this project was generated via quantum Monte Carlo simulations with the worm algorithm
Processed and the raw simulation data set is available online at [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10137837.svg)](https://doi.org/10.5281/zenodo.10137837).

1. A minimal environment to execute these notebooks can be installed via `pip install -r requirements.txt`
2. All quantum Monte Carlo data was generated with our [open source path integral software](https://code.delmaestro.org) also available on [github](https://github.com/delmaestrogroup/pimc)

### Support
This research was partially supported by the National Science Foundation Materials Research Science and Engineering Center program through the UT Knoxville Center for Advanced Materials and Manufacturing (DMR-2309083).

### Figures

#### Figure 01: Simulation cell in the x-y plane.
<img src="https://github.com/DelMaestroGroup/papers-code-GrapheneCorrugation/blob/main/figures/Fig1.svg" width="400px">

#### Figure 02: Potential Analysis in the z and xy plane. 
<img src="https://github.com/DelMaestroGroup/papers-code-GrapheneCorrugation/blob/main/figures/Fig2.svg" width="400px">

#### Figure 03: Filling fraction in the first layer.
<img src="https://github.com/DelMaestroGroup/papers-code-GrapheneCorrugation/blob/main/figures/Fig3.svg" width="400px">

#### Figure 04: Energy per particle in the first layer regime.
<img src="https://github.com/DelMaestroGroup/papers-code-GrapheneCorrugation/blob/main/figures/Fig4.svg" width="400px">

#### Figure 05: Compressibility as a function of chemical potential.
<img src="https://github.com/DelMaestroGroup/papers-code-GrapheneCorrugation/blob/main/figures/Fig5.svg" width="400px">

#### Figure 06: Filling fraction in the second layer regime and linear density.
<img src="https://github.com/DelMaestroGroup/papers-code-GrapheneCorrugation/blob/main/figures/Fig6.svg" width="400px">

#### Figure 07: Energy per particle in the second layer regime.
<img src="https://github.com/DelMaestroGroup/papers-code-GrapheneCorrugation/blob/main/figures/Fig7.svg" width="400px">


