# CMB / BAO from G4 — all closed relations

S2-11DM2ET-X  Category B  2026-09-20

G4=539.9  D=11  cubic=27  N_flux=4880
kappa_dark=243/539  f_snap=243/4880  mu=1.55  S=0.31
Planck theta_* is not an input. Dip language is retired.


## TT positions

ell_1 = G4*11/27 = 219.959     Planck 220.6 ± 0.6    -0.29%
ell_2 = G4       = 539.9       Planck 538.1 ± 1.3    +0.33%
ell_3 = G4*3/2   = 809.85      Planck 809.8 ± 1.0    +0.006%
ell_4 = G4*17/8  = 1147.287    Planck 1147.8 ± 2.3    -0.04%
ell_5 = G4*8/3   = 1439.73     Planck 1446.8 ± 1.6    -0.49%
ell_6 = G4*(27-4)/7 = 1773.96  Planck 1779 ± 3        -0.28%
ell_7 = G4*27/7  = 2082.47     Planck 2075 ± 8        +0.36%
ell_T2= G4*5/4   = 674.875     Planck 675.5 ± 1.2    -0.09%
ell_T5= 3 G4     = 1619.70     Planck 1623.8 ± 2.1    -0.25%
ell_T6= G4*32/9  = 1919.64     Planck 1919 ± 4        +0.03%

After peak 5 (diffusion scale) the remaining peaks live on the TE 7-grid:
ell_n = G4 (27 - 4*(7-n)) / 7   for n=6,7
4 is the TE residue already used in ell_TE,1=G4*4/7. Not a new generator.


## EE positions and ratios

ell_EE,1 = G4*3/11 = 147.245
ell_EE,n = G4*(6n-4)/11          (n>=2)
EE2/EE1 = G4/27
EE3/EE2 = 11/6
Absolute EE muK not claimed.


## Silk

ell_D = G4*8/3 = 1439.73
ell_t = G4*11/5 = 1187.78
ell_S = 916.3


## Heights

P1/P2 = 1/kappa_dark = 539/243                      -0.05%
P3/P1 = (1-kappa_dark) exp(-(ell_3^2-ell_1^2)/(3 G4)^2)   -0.8%
P4/P2 = kappa_dark (1+f_snap)                         -0.25%
P5/P3 = (1-kappa_dark) exp(-(ell_5^2-ell_3^2)/(3 G4)^2)   +0.84%
P6/P4 = S = 0.31                                      +0.6%
P7/P5 = S (1-1/D) = 0.31*10/11 = 0.2818               -0.8%


## BAO and warp

D_M(z_*) = 3(N_flux-3^5) Mpc = 13911 Mpc
ell_A = G4(mu-1) = 296.945
r_d = pi*13911/296.945 = 147.15 Mpc

Omega_m = (2/3) kappa_dark = 162/539 = 0.30056
Omega_DE = 377/539
w = -1 + f_snap = -1 + 243/4880 = -0.9502
H0 = 68.15 km s^{-1} Mpc^{-1}   (from chi(z_*) at this w and D_M(z_*))
h r_d = 100.30 Mpc                DESI 101.54 ± 0.73   -1.2%

Leading D2 warp is constant snap correction to w. A z-dependent sech/exp trial raised D_M residuals and is not adopted.
LRG1 D_H(z=0.51) stays a DESI-side residual (~2.5% at this w), not a new model parameter.
