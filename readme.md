# The many colors of the TNG100 simulation
This repository contains a notebook and some data to reproduce all figures from Gebek et al. 2024, in which we present and analyze broadband fluxes for TNG100 galaxies computed with the 3D dust radiative transfer code SKIRT. Simply sit back, run the analysis notebook, and enjoy! On a decent laptop the whole analysis takes a few minutes. If you have any questions please reach out to andrea.gebek@ugent.be!

## Software Requirements
The notebook includes a more detailed list of required python packages. Most of them are commonly found on astrophysicist devices, with one exception:
ndtest (https://github.com/syrte/ndtest)

The ndtest package is required to perform 2D Kolmogorow-Smirnov tests, and is not critical for the results. Hence, the notebook can easily be adapted so that ndtest is not required.

## Data Requirements
No SKIRT data is uploaded to this repository since these files are relatively large. Hence, these files need to be downloaded from the IllustrisTNG website. See the notebook for more information.