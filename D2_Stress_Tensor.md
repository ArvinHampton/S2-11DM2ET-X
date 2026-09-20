# D2 stress tensor

From S_D2 = -T_2 \int d^3\xi \sqrt-\gamma only.

## Embedding

\xi = (t, x_parallel, y). X^t=t, X^parallel=x_parallel, X^y=y, X_perp=const.

ds^2 = e^{-2k b y} (-dt^2 + a^2 dx_parallel^2 + a^2 dx_perp^2) + b^2 dy^2

\gamma_tt = -e^{-2kby}, \gamma_parallel = a^2 e^{-2kby}, \gamma_yy = b^2
\sqrt-\gamma = a b e^{-2kby}
\sqrt-g = a^3 b e^{-4kby}

## Bulk tensor

T^{AB} = -2/\sqrt-g \delta S_D2/\delta g_{AB}
       = -T_2 \int d^3\xi (\sqrt-\gamma/\sqrt-g) \gamma^{ab} \partial_a X^A \partial_b X^B \delta^5(x-X)

\sqrt-\gamma/\sqrt-g = e^{2kby}/a^2

T^{tt} = T_2 e^{4kby} a^{-2} \delta^2(x_perp)
T^{parallel parallel} = -T_2 e^{4kby} a^{-4} \delta^2(x_perp)
T^{yy} = -T_2 e^{2kby} /(a^2 b^2) \delta^2(x_perp)
T^{perp perp} = 0

\rho_5 = T_AB u^A u^B = T_2 a^{-2} e^{2kby} \delta^2(x_perp)

u^A = (e^{kby}, 0)

Worldvolume directions are tension. Transverse pressures vanish.

## Smear

\delta^2(x_perp) \to n_2 (comoving number per transverse area).

## On +U

T^{(H)}_{\mu\nu} = -2/\sqrt-q_+ \delta S_D2/\delta q_+^{\mu\nu}

At y=0, after smear:
\rho_H = n_2 T_2 b,  p_parallel = -\rho_H,  p_perp = 0

Isotropic DE: average over D2s wrapping each +U axis.
Match today: n_2 T_2 b_0 = \rho_DE(0)

Current T^y_t carries one power of the lapse:
\rho_H(b) = \rho_DE(0) e^{-k(b-b_0)} = \rho_DE(0) \kappa_dark^{b/b_0-1}

Product n_2 T_2 b_0 is fixed. T_2 and n_2 separately are not.
