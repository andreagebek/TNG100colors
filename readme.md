# The many colors of the TNG100 simulation
This repository contains a notebook and some data to reproduce all figures from Gebek et al. 2024, in which we present and analyze broadband fluxes for TNG100 galaxies computed with the 3D dust radiative transfer code SKIRT. Simply sit back, run the analysis notebook, and enjoy! On a decent laptop the whole analysis takes a few minutes.

## Software Requirements
The notebook includes a more detailed list of required python packages. Most of them are commonly found on astrophysicist devices, with two exceptions:
illustris_python 1.0.0 (https://github.com/illustristng/illustris_python)\
ndtest (https://github.com/syrte/ndtest)\
\
The illustris_python package is needed to read in the TNG subhalo catalogues and must be installed before running the analysis notebook. The ndtest package is required to perform 2D Kolmogorow-Smirnov tests, and is not critical for the results. Hence, the notebook can easily be adapted so that ndtest is not required.

## Data Requirements
No IllustrisTNG data is uploaded to this repository since these files are available online at the [IllustrisTNG](www.tng-project.org) website. Specifically, subhalo catalogues and SKIRT files for TNG100-1 and TNG50-1 at snapshots 99 and 91 are required. See the analysis notebook or the IllustrisTNG documentation for more information.