# Kepler-167-Posteriors
This repository contains the a-posteriori distributions of parameters for Kepler-167 planetary system, as derived in the paper:

Kipping, D. M., Torres, G., Henze, C., Teachey, A., Isaacson, H., Petigura, E., Marcy, G. W., Buchhave, L. A., Chen, J., Bryson, S. T. & Sandford, E. 2016, ApJ, accepted

There are three sets of files:

K167_post = posteriors for the host star, Kepler-167

K167bcd_post = posteriors for planets Kepler-167b,c & d from a joint transit light curve fit

K167e_post = posteriors for planet Kepler-167e from a transit light curve fit

Each .dat file contains 20,000 fair samples drawn from the full posteriors. Each .pdf file displays a triangle plot (generated using https://github.com/dfm/corner.py).

Columns for K167_post.dat

[1] Effective Temperature, T_eff [Kelvin]

[2] Metallically, Fe/H

[3] Stellar Mass, M_* [Solar Masses]

[4] Stellar Radius, M_* [Solar Masses]

[5] Log Surface Gravity, log g [dex]

[6] Log Luminosity, log L [dex]

[7] Age [Gyr]

Columns for K167bcd_post.dat

[1] Log Stellar Density, log rho* [dex]

[2] Reparametrized Quadratic Limb Darkening Coefficient 1, q1

[3] Reparametrized Quadratic Limb Darkening Coefficient 2, q2

[4] Log Flux Ratio of Companion:Primary [dex]

[5] Ratio-of-Radii for Planet b

[6] Impact Parameter for Planet b

[7] Orbital period for Planet b [days]

[8] Time of Transit Minimum for Planet b [BJD_UTC - 2,400,000]

[9] Ratio-of-Radii for Planet c

[10] Impact Parameter for Planet c

[11] Orbital period for Planet c [days]

[12] Time of Transit Minimum for Planet c [BJD_UTC - 2,400,000]

[13] Ratio-of-Radii for Planet d

[14] Impact Parameter for Planet d

[15] Orbital period for Planet d [days]

[16] Time of Transit Minimum for Planet d [BJD_UTC - 2,400,000]

Columns for K167e_post.dat

[1] Log Stellar Density, log rho* [dex]

[2] Reparametrized Quadratic Limb Darkening Coefficient 1, q1

[3] Reparametrized Quadratic Limb Darkening Coefficient 2, q2

[4] Log Flux Ratio of Companion:Primary [dex]

[5] Ratio-of-Radii for Planet b

[6] Impact Parameter for Planet b

[7] Orbital period for Planet b [days]

[8] Time of Transit Minimum for Planet b [BJD_UTC - 2,400,000]

[9] Eccentricity for Planet e

[10] Argument of Periastron for Planet e [rads]
