# 3DPolyS-Epi: *Polymer simulations of 3D epigenome folding*


external link: https://github.com/physical-biology-of-chromatin/3DPolyS-Epi

developed by D. Jost, Jost Lab, LBMC, ENS de Lyon/CNRS

## Description

The 1D segmentation of the genome into epigenomic domains is tightly correlated to the 3D chromatin organization. To investigate the mechanistic foundations of this coupling, we developed polymer models to better characterize how epigenomically-associated mechanisms drive chromosome organization. We assumed that regions sharing the same epigenomic state can interact at short-range. The dynamics of the polymeric chain is then driven by these interactions and by excluded volume. To simulate this dynamics, we developed a kinetic Monte-Carlo algorithm applied to lattice polymers (see corresponding references for details on the methods). We implemented two versions: *3DPolyS-Epi.Energy* where the interactions are driven by short-range potentials and the dynamics followed a Metropolis criterion; *3DPolyS-Epi.Link* where interactions are modeled as transient links that formed and disassembled dynamically with a control on the average lifetime of the link. 

## How to cite
*3DPolyS-Epi.Energy:* S.K. Ghosh & D. Jost (2018) How epigenome drives chromatin folding and dynamics, insights from efficient coarse-grained models of chromosomes. PLoS Comp. Biol. 14, e1006159.

*3DPolyS-Epi.Link:* M. Socol, R. Wang, D. Jost et al (2019) Rouse model with transient intramolecular contacts on a timescale of seconds recapitulates folding and fluctuation of yeast chromosomes. Nucleic Acids Res. 47, 6195-6207.

