# CMB / BAO from G4 — corrected record

S2-11DM2ET-X  Category B  2026-09-20

G4 = 539.9. D = 11. Cubic = 27. N_flux = 4880.
kappa_dark = 243/539. f_snap = 243/4880. mu = 1.55.
Planck theta_* is not an input. Dip language is retired.


## TT positions

ell_1 = G4 * 11/27 = 219.959     Planck 220.6 ± 0.6    -0.29%
ell_2 = G4         = 539.9       Planck 538.1 ± 1.3    +0.33%
ell_3 = G4 * 3/2   = 809.85      Planck 809.8 ± 1.0    +0.006%
ell_4 = G4 * 17/8  = 1147.287    Planck 1147.8 ± 2.3    -0.04%
ell_5 = G4 * 8/3   = 1439.73     Planck 1446.8 ± 1.6    -0.49%
ell_T2= G4 * 5/4   = 674.875     Planck 675.5 ± 1.2    -0.09%
ell_T5= 3 G4       = 1619.70     Planck 1623.8 ± 2.1    -0.25%
ell_T6= G4 * 32/9  = 1919.64     Planck 1919 ± 4        +0.03%

Peak 5 sits at the diffusion scale (same 8/3 as ell_D).
ell_6, ell_7 on the TE 7-grid are candidates, not closed.


## EE positions

ell_EE,1 = G4 * 3/11        = 147.245     Planck 145 ± 3       +1.5%
ell_EE,n = G4 * (6n-4)/11
 n=2: 8/11  = 392.655                   Planck 398.3 ± 1.0   -1.4%
 n=3: 14/11 = 686.236                   Planck 690.4 ± 1.2   -0.6%
 n=4: 20/11 = 981.636                   Planck 993.1 ± 1.8   -1.2%
 n=5: 26/11 = 1276.04                   Planck 1296.4 ± 4.3  -1.6%

EE2/EE1 = G4/27 = 19.996                Planck 19.32           +3.5%
EE3/EE2 = 11/6  = 1.833                 Planck 1.776           +3.2%
Absolute EE muK not claimed.


## Silk

ell_D = G4 * 8/3  = 1439.73
ell_t = G4 * 11/5 = 1187.78
ell_S^{-2} = ell_D^{-2} + ell_t^{-2}  =>  ell_S = 916.3


## Heights

P1/P2 = 1/kappa_dark = 539/243 = 2.2181     Planck 2.2169    -0.05%
P3/P1 = (1-kappa_dark) exp(-(ell_3^2-ell_1^2)/(3 G4)^2) = 0.4358
                                            Planck 0.4392    -0.8%
P4/P2 = kappa_dark (1+f_snap) = 0.47328     Planck 0.47448   -0.25%
P5/P3 = (1-kappa_dark) exp(-(ell_5^2-ell_3^2)/(3 G4)^2) = 0.3200
                                            Planck 0.3173    +0.84%


## BAO + leading-order warp

D_M(z_*) = 3 (N_flux - 3^5) Mpc = 13911 Mpc
ell_A = G4 (mu - 1) = 296.945
r_d = pi * 13911 / 296.945 = 147.15 Mpc

Omega_m = (2/3) kappa_dark = 162/539 = 0.30056
Omega_DE = 377/539 = 0.69944
w = -1 at leading order
H0 = c * chi(z_*) / D_M(z_*) = 68.45 km s^{-1} Mpc^{-1}
h r_d = 100.74 Mpc                         DESI 101.54 ± 0.73  -0.79%

LRG1 D_H at z=0.51 remains the open warp residual (~3%).
