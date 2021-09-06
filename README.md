# EPSC2021-484
Supplement material for poster presentation "Implications of a realistic crustal rheology for Venus’ resurfacing history and global tectonics" at EPSC 2021 (https://doi.org/10.5194/epsc2021-484)

# Methodlogy
- Geodynamic model in 2D spherical annulus geometry, using the finite volume code StagYY (Tackley, 2008, *PEPI*) 
  - Composite rheology: diffusion creep, dislocation creep, and plastic yielding
  - Reference viscosity = <!-- $1*10^{20} \mathrm{Pa\cdot s}$ --> <img style="transform: translateY(0.1em); background: white;" src="svg/vMnZfz6iHW.svg"> 
<!-- $$
\eta_{\mathrm{composite}} = \min(\frac{1}{1/\eta_{\mathrm{diff}}+1/\eta_{\mathrm{disl}}}, \frac{\sigma_{\mathrm{yield}}}{2\dot{\epsilon}})
$$ --> 
  

<div align="center"><img style="background: white;" src="svg/gkh4VP6oyO.svg"></div> 

- Phase system: olivine and pyroxene-garnet, the parameterization is similar with (Nakagawa & Tackley, 2012, *EPSL*)

- For basalt facies (or the shallowest facies) in pyroxene-garnet system, a plagioclase rheology (An75) from (Ranalli, 1995) is applied.
  - Olivine rheology is applied to other phases, based on (Karato & Wu, 1993, *Science*) for the upper mantle and (Yamazaki & Karato, 2001, *Am. Mineral.*; Ammann et al., 2010, *Nature*) for the lower mantle.

- Melting: intrusion and eruption, the parameterization is similar with (Lourenço et al., 2020, *G3*)



# Cases
- M0: composite rheology with diffusion creep , dislocation creep, and plastic yielding, cohesion = 0.3 MPa, friction coefficient = 0.2, An75 for basalt facies

- M1: composite rheology same with M0 except olivine for basalt facies 



---
As we reran the reference model(M0) with the same parameters, the results displayed here is a bit different from figures in the abstract: there are global and regional overturns, but the timings for overturns are different, not at 1.65 and 2.61 Ga. Also, the patterns for mobility are different, but both show a high and continous mobility when plagioclase rheology is applied to the basaltic crust.


