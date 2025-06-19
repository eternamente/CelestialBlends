# kiauhoku
[git link](https://github.com/zclaytor/kiauhoku)
## kiauhoku output params for fastlaunch grid
| Parameter          | Description                                                                                  | Units                   |
|--------------------|---------------------------------------------------------------------------------------------|-------------------------|
| Age(Gyr)           | Stellar age                                                                                 | Gigayears (Gyr)         |
| L/Lsun             | Luminosity relative to the Sun                                                              | L☉       |
| R/Rsun             | Radius relative to the Sun                                                                  | R☉       |
| Log Teff(K)        | Logarithm (base 10) of the effective temperature                                            | log(K)   |
| Mcz(Msun)          | Mass of the convective zone                                                                 | M☉       |
| Rcz(Rsun)          | Radius at the base of the convective zone                                                   | R☉       |
| Xcen               | Central hydrogen mass fraction                                                              | -        |
| Itot(cgs)          | Total moment of inertia                                                                     | g·cm²    |
| Icz(cgs)           | Moment of inertia of the convective zone                                                    | g·cm²    |
| Tau(cz)(sec)       | Convective turnover time                                                                    | s        |
| He Core(Msun)      | Helium core mass                                                                            | M☉       |
| Patm(cgs)          | Surface atmospheric pressure                                                                | dyn/cm²  |
| Mass(Msun)         | Stellar mass in solar units                                                                 | M☉       |
| Prot(days)         | Surface rotation period                                                                     | days     |
| Icore(cgs)         | Moment of inertia of the stellar core                                                       | g·cm²    |
| Omega(core)        | Angular velocity of the core                                                                | rad/s    |
| Omega(env)         | Angular velocity of the envelope                                                            | rad/s    |
| Jtot(cgs)          | Total angular momentum                                                                      | g·cm²/s  |
| Jcore(cgs)         | Angular momentum of the core                                                                | g·cm²/s  | 
| Jenv(cgs)          | Angular momentum of the envelope                                                            | g·cm²/s  |
| logg               | Logarithm (base 10) of the surface gravity                                                  | log(cm/s²)   |
| logT(cen)          | Logarithm (base 10) of central temperature                                                  | log(K)       |
| logrho(cen)        | Logarithm (base 10) of central density                                                      | log(g/cm³)   |
| Ycen               | Central helium mass fraction                                                                | - (fraction) |
| XC12cen            | Central carbon-12 mass fraction                                                             | - (fraction) |
| Xsurf              | Surface hydrogen mass fraction                                                              | - (fraction) |
| Ysurf              | Surface helium mass fraction                                                                | - (fraction) |
| Z/X(surf)          | Surface heavy element to hydrogen mass ratio                                                | - (dimensionless ratio)|
| H lum (Lsun)       | Luminosity from hydrogen burning                                                            | Solar luminosities      |
| He lum (Lsun)      | Luminosity from helium burning                                                              | Solar luminosities      |

## kiauhoku output params for MIST grid

| Parameter                 | Description                                        | Units              |
|---------------------------|----------------------------------------------------|--------------------|
| star_age                  | Stellar age                                        | years              |
| star_mass                 | Stellar mass                                       | M☉                 |
| star_mdot                 | Mass-loss rate                                     | M☉/year            |
| he_core_mass, c_core_mass, o_core_mass | Core masses of He, C, O            | M☉                 |
| log_L                     | log₁₀(Luminosity / L☉)                            | log(L☉)            |
| log_L_div_Ledd            | log₁₀(L/L_Eddington)                              | -                  |
| log_LH, log_LHe, log_LZ   | log luminosity from H/He/other burning             | log(L☉)            |
| log_Teff                  | log₁₀(Effective temperature)                      | log(K)             |
| log_abs_Lgrav             | log₁₀(|Gravitational Luminosity|)                 | -                  |
| log_R                     | log₁₀(Stellar radius / R☉)                        | log(R☉)            |
| log_g                     | log₁₀(Surface gravity)                            | log(cm/s²)         |
| log_surf_z                | log₁₀(Surface heavy-element mass fraction Z)      | -                  |
| surf_avg_omega            | Surface average angular velocity                   | rad/s              |
| surf_avg_v_rot            | Surface average rotational velocity                | km/s               |
| surf_num_c12_div_num_o16  | Surface num. ratio C12/O16                        | -                  |
| v_wind_Km_per_s           | Surface wind velocity                             | km/s               |
| surface_h1                | Surface hydrogen mass fraction                     | -                  |
| surface_he4               | Surface helium-4 mass fraction                    | -                  |
| surface_c12, surface_o16  | Surface C12, O16 mass fractions                    | -                  |
| log_center_T              | log₁₀(Central temperature)                        | log(K)             |
| log_center_Rho            | log₁₀(Central density)                            | log(g/cm³)         |
| center_degeneracy         | Central electron degeneracy parameter              | -                  |
| mass_conv_core            | Mass convective core                               | M☉                 |
| center_h1, center_he4     | Central H1/He4 mass fractions                      | -                  |
| pp, cno, tri_alfa         | log(energy production rates for pp, CNO, 3α)       | log(erg/s) or -    |
| burn_c, burn_n, burn_o    | log(energy prod. for C/N/O burning)                | log(erg/s) or -    |
| c12_c12                   | log(rate for 12C+12C reactions)                    | log(reactions/s)   |
| delta_nu                  | Large frequency separation (asteroseismology)      | μHz                |
| nu_max                    | Frequency of maximum oscillation power             | μHz                |
| acoustic_cutoff           | Acoustic cutoff frequency                          | μHz                |
| e_thermal                 | Thermal energy content                             | erg                |
| phase                     | Evolutionary phase index                           | -                  |

## All grids in kiauhoku
source link: (zenodo)[https://zenodo.org/records/11264222]

| Grid Name    | Full Name                           | Dimensions | Index Parameters              | Key Features                    | Reference                | Reference/Notes                                           |
|--------------|-------------------------------------|------------|-------------------------------|--------------------------------|--------------------------|----------------------------------------------------------|
| **mist**         | MESA Isochrones & Stellar Tracks    | 3D         | mass, metallicity, eep        | Modern MESA models, detailed    | Choi et al. (2016)       | Solar-scaled, single stars                               |
| **yrec**         | Yale Rotating Evolution Code        | 4D         | mass, metallicity, alpha, eep | Rotation effects, magnetic braking | Spada et al. (2013)    | Rotational/magnetic versions exist                      |
| **dartmouth**| Dartmouth Stellar Evolution         | 3D         | mass, metallicity, eep        | Classic grid, well-tested       | Dotter et al. (2008)     | Well-tested for low-mass stars                          |
| **garstec**      | Garching Stellar Evolution Code     | 3D         | mass, metallicity, eep        | Convective overshooting         | Weiss (1987)             | Grid for various [Fe/H]                                 |
| **fastlaunch**| Rotating models (fast rotation)    | 4D         | mass, metallicity, alpha, eep | Gyrochronology, rotation        | Claytor et al. (2020)    | For rotation, with α-enhancement                        |
| **slowlaunch**| Rotating models (slow rotation)    | 4D         | mass, metallicity, alpha, eep | Gyrochronology, rotation        | Claytor et al. (2020)    | Like fastlaunch, for slow rotators                      |
| **rocrit**       | Rotation at critical velocity       | 4D         | mass, metallicity, alpha, eep | Critical rotation effects       | Claytor et al. (2020)    | For rotation, magnetic effects                          |

## EEP (Equivalent Evolutionary Point)
sourse: https://www.aanda.org/articles/aa/full_html/2021/03/aa39357-20/T2.html
### Correspondance between equivalent evolutionary points (EEPs) and stellar evolutionary phase
| EEP  | Phase                                | Abbreviation |
|------|--------------------------------------|--------------|
| 1    | Pre-main sequence                    | PMS          |
| 202  | Zero age main sequence               | ZAMS         |
| 353  | Intermediate age main sequence       | IAMS         |
| 454  | Terminal age main sequence           | TAMS         |
| 605  | Tip of the red giant branch          | RGBTip       |
| 631  | Zero age core helium burning         | ZACHeB       |
| 707  | Terminal age core helium burning     | TACHeB       |

## Directory grids example
Downloads from zendo, example: https://zenodo.org/record/{record_id}/files/yrec_eep.tar.gz
```
~/.kiauhoku/grids/
├── yrec/
│   ├── yrec_eep.pqt         
│   ├── yrec_interpolator.pkl  
│   └── yrec_eep_params.pkl   # EEP params
├── mist/
│   ├── mist_eep.pqt
│   ├── mist_interpolator.pkl
│   └── mist_eep_params.pkl
├── dartmouth/
└── garstec/
```
# ARIADNE
[git link](https://github.com/jvines/astroARIADNE)
## ARIADNE input parameters

| Parameter         | Description                                         | Units / Example             |
|-------------------|-----------------------------------------------------|-----------------------------|
| starname          | Star identifier/name                                | string (exampe, WASP-19)    |
| ra                | Right Ascension (J2000)                             | degrees                     |
| dec               | Declination (J2000)                                 | degrees                     |
| g_id              | Gaia ID (optional, for auto-photometry)             | -                           |
| photometry        | Photometric bands + magnitudes (+errors)            | example, V=10.34, err=0.03  |
| filters           | List of bands (if not auto)                         | example ['V', 'J', 'K']     |
| distance/parallax | Distance (pc) or Gaia parallax (mas & error)        | pc / mas                    |
| Av                | Extinction                                          | mag                         |
| metallicity (z)   | Metallicity [Fe/H]                                  | dex                         |
| priors            | Priors on parameters (optional, advanced)           | ('default'), or custom      |

## ARIADNE output parameters

| Parameter    | Description                                          | Units                    |
|--------------|------------------------------------------------------|--------------------------|
| teff         | Effective temperature                                | K                        |
| logg         | Surface gravity (log10)                              | log(cm/s²)               |
| z            | Metallicity [Fe/H]                                   | dex                      |
| radius       | Stellar radius                                       | R☉                       |
| distance     | Distance (if not fixed)                              | pc                       |
| norm         | Normalization factor (if normalization mode used)    | -                        |
| Av           | Extinction                                           | mag                      |
| lum          | Stellar luminosity                                   | L☉                       |
| best_fit     | Best-fit parameters and uncertainties                | -                        |
| model_sed    | Synthetic SED (array, optionally saved to .dat)      | -                        |
| posteriors   | Posterior samples (arrays for each param)            | -                        |
| chain_plots  | MCMC trace/corner/posterior/HR histograms (figures)  | -                        |
| IR excess    | IR-excess indication/plot (if enabled)               | -                        |
