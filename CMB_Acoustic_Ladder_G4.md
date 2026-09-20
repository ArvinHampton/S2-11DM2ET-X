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
ell_T2= G4 * 5/4   = 674.875     Planck 675.5 ± 1.2    -0.09%

Peak 1 = first compression = 11D on the +U 3-cube.
Peak 2 = first completed flux period.
Peak 3 = h_j = 3/2 overtone.
Peak 4 = 2 + 1/8.


## EE positions

ell_EE,1 = G4 * 3/11        = 147.245     Planck 145 ± 3       +1.5%
ell_EE,n = G4 * (6n-4)/11
 n=2: 8/11  = 392.655                   Planck 398.3 ± 1.0   -1.4%
 n=3: 14/11 = 686.236                   Planck 690.4 ± 1.2   -0.6%
 n=4: 20/11 = 981.636                   Planck 993.1 ± 1.8   -1.2%
 n=5: 26/11 = 1276.04                   Planck 1296.4 ± 4.3  -1.6%

EE2/EE1 = G4/27 = 19.996                Planck 21.45/1.11 = 19.32   +3.5%
EE3/EE2 = 11/6  = 1.833                 Planck 38.1/21.45 = 1.776   +3.2%


## Silk

ell_D = G4 * 8/3  = 1439.73
ell_t = G4 * 11/5 = 1187.78
ell_S^{-2} = ell_D^{-2} + ell_t^{-2}  =>  ell_S = 916.3


## Heights

P1/P2 = 1/kappa_dark = 539/243 = 2.2181     Planck 5733/2586 = 2.2169    -0.05%

P3/P1 = (1 - kappa_dark) * exp( -(ell_3^2 - ell_1^2) / (3 G4)^2 )
      = (296/539) * exp( -(809.85^2 - 219.96^2) / 1619.7^2 )
      = 0.54917 * 0.7935 = 0.4358           Planck 2518/5733 = 0.4392    -0.8%

3 G4 is the three-generation odd-peak damping clock.


## BAO length

D_M(z_*) = 3 (N_flux - 3^5) Mpc = 3*4637 = 13911 Mpc
ell_A = G4 (mu - 1) = 296.945
theta_* = pi / ell_A = 0.010577
r_d = theta_* D_M = pi * 13911 / 296.945 = 147.15 Mpc

Planck/DESI fiducial r_d ~ 147.05 to 147.09 Mpc. Residual ~ +0.07%.
c*G4 is not this ruler (Clock III).


## Spectrum

C_ell = A_H-QP * sum_n H_n P(ell - ell_n[G4,11]) * S_silk(ell)
      + delta C^{-U} sin(2 pi ell / G4 + phi_11)

H_odd/H_even at first pair = 539/243.
