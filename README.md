# Dynamical Diffraction using Wie algorithm

Mostly written and maintained by [Eric Landahl, DePaul University Physics Dept.](https://sites.google.com/site/elandahl/)

## Run benchmark
The main program to run is TXRD_Driver_example.m
Set model = 'benchmark' on Line 15 to run comparisson to GID.
The actual strain profile is specified in TRXD.m, lines 169-178.
Details on the benchmarking and simple results are found in /benchmarks folder.

## For help
In MatLab or Octave type `help filename`

## Update 1/19/2017
Works for GaAs, Si, InSb, Ge, [004] reflection only, 7-15 keV

## To Do List
- [x] Fix incompatibilities with standard MatLAB functions
- [x] Handle a few simple bulk crystals over a reasonable energy range (7 - 15 keV)
*  GaAs
*  Si
*  InSb
*  Ge
- [x]  Develop an easy to use driver to TRXD calling various strain functions
- [ ] Transverse and shear strain, benchmarked to GID

## Develop simple strain functions
- [X] Thermal diffusion
- [ ] Simple mean free path modified thermal diffusion model
- [ ] Electron diffusion with Auger and radiative decay
- [ ] Thomsen model
- [ ] Arbitrary strain propogation (e.g. Diffusion drives strain)
- [ ] Noninear absorption (e.g. Saturable Absorption, Two Photon Absorption)
- [ ] More sophisticated models for nanoscale thermal and electrical transport


