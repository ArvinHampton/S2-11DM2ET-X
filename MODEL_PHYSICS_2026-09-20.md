# S²-11DM²ET-X physics hold — 2026-09-20

Category B continuum / observational layer.
Canonical constants from 539-Labs-Master CLOSED_CONSTANTS.md.
Lattice QCD is not applied to muon g-2 until Belle II 2π or MUonE / J-PARC.
G4 = 539.9 s is immutable.


## Closed constants used here

    G4        = 539.9 s
    D         = 11
    sigma     = 539
    kappa_dark = 243/539     (~0.45083; slogan 0.45)
    beta_PBH   = 11/61       (~0.18033; slogan 0.18)
    f_snap     = 243/4880    (~0.04980; slogan 0.05)
    S          = 0.31
    mu         = 1.55
    mu/Omega_DE cap = 0.68
    S/kappa_dark    = 0.31 / 0.45083 ~ 0.688 ~ 0.68

Algebraic beta_PBH = 11/61 is not a stellar-mass dark-matter fraction.
LVK O4a bounds f_PBH ~ 10^{-4} to 10^{-2} in 0.6-100 M_sun.
Physical stellar-mass window: f_PBH << 11/61. Asteroid / evaporating windows remain open for the algebraic ratio.


## Muon g-2

Experimental world average after Fermilab Run 1-6 (2025):

    a_mu^exp = 116592071.5(14.5) e-11

WP25 adopted lattice LO-HVP and quotes Delta a_mu = 38(63) e-11 versus experiment.
That lattice / hybrid closure is logged and not subtracted here.
Belle II e+e- -> pi+pi- gamma on ~428 fb^{-1} remains blinded (Sept 2025 status: 1.856 fb^{-1} sanity check).
Belle II 3pi is 2.5 sigma high versus BaBar. BaBar 2025 2pi re-analysis confirms BaBar 2009.
CMD-3 versus KLOE remains unresolved. No data-driven WP25 HVP average exists.

Hold:

    Delta a_mu^{exp-disp} frozen at the WP20-style residual until Belle II 2pi
    delta a_mu^{-U} remains a free -U leakage coefficient
    lattice HVP does not enter E_leak

Muon block:

    E_leak^mu(t) = (Delta a_mu^{exp-disp} + delta a_mu^{-U})
                   * (g_{-U}^2 m_mu^2) / (8 pi^2 M_{-U}^2)
                   * kappa_dark
                   * sin(2 pi t / 539.9)


## CMB

See CMB_Acoustic_Ladder_G4.md.

Retired: dip at ℓ = 539.9.
Installed: ℓ_n = ℓ_n[G4, 11] as model output.


## Gravitational waves

Retired: "LIGO O5 2026".
O4c ended 2025-11-18.
Next public window: LVK IR1, about six months, start late Oct to mid Nov 2026.
O5 is not 2026 (planning language: late 2027 onward).

Search template unchanged:

    sin(2 pi t / 539.9)

Narrowband search required. O4a all-sky burst and isotropic-background papers do not test this line.


## Hubble, S8, dark energy

Tensions remain in 2026 datasets (SH0ES-class H0, DES Y6 S8 low versus combined CMB, DESI DR2 evolving w(z)).
Those tensions are allowed room for leakage / kappa_dark running.
They are not unique confirmations of D2-brane transfer.
Optional: slow z-running of kappa_dark or Phi to shadow DESI w(z). No retune of mu = 1.55 until a dataset measures that combination.


## Strong CP

Still open. |theta_bar| ≲ 10^{-10} from nEDM. No new dataset confirms an 11D solution.


## Rules that did not move

- Ignore SM lattice QCD for muon g-2 until Belle II / independent HVP.
- 539.9 s flux is immutable.
- 11D caps divergences (mu / Omega_DE = 0.68).
- Sums and integrals exact.
- Twin Prime and RH unclaimed.
- Continuum G4 mappings stay Category B.
