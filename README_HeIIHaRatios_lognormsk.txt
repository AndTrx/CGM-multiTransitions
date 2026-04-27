Repository: HeII/Halpha line-ratio models

This repository contains the electronic table associated with our analysis of the HeII/Halpha emission-line ratio.

File:
HeIIHaRatios_lognormsk.csv

Description:
The table reports the HeII/Halpha line ratio computed across the full parameter grid explored in the paper. For each model, the line emissivities are weighted by a skewed log-normal density distribution.

Columns:
alpha_EUV      : EUV spectral slope of the ionizing source
Magnitude      : absolute magnitude M_1450
Dist_kpc       : cloud distance from the ionizing source, in kpc
Size_pc        : cloud size, in pc
n0_cm3         : reference gas density, in cm^-3
sigma          : dispersion of the log-normal density distribution
alpha_skew     : skewness parameter of the skewed log-normal distribution
HeII_Ha_ratio  : resulting HeII/Halpha line ratio

Parameter ranges:
alpha_EUV  = -1.7, -2.2
M_1450     = -27, -29
D_c        = 10, 50 kpc
l_c        = 70, 200 pc
n0         = 10^-3 to 10^-1 cm^-3
sigma      = 0 to 4, in steps of 0.05
alpha_skew = 0 to 3, in steps of 0.25

Notes:
The table is intended as a reference dataset to reproduce and explore the dependence of the HeII/Halpha line ratio on the density distribution parameters and on the physical parameters adopted in the paper.

Please cite the associated paper if you use this table created by Travascio Andrea.