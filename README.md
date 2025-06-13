## kiauhoku params
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



