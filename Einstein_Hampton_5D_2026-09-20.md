# Einstein-Hampton equation

20 September 2026

## Bulk

G_AB + Lambda_5 g_AB = 8 pi G_5 T^(D2)_AB

Lambda_5 = -6 k^2 (M_5^3=1). G_5 from G_4:

8 pi G_5 = 8 pi G_4 * (1 - kappa_dark^2) / k

## Metric

ds^2 = e^{-2 k b(t) y} (-dt^2 + a(t)^2 dx^2) + b(t)^2 dy^2,  y in [0,1]

+U at y=0, -U at y=1. D2 wraps t x x_parallel x y.

## Junctions

Israel at each brane. RS tune tau^+ = - tau^- = 6k. Snap: tau^- -> tau^- (1+f_snap). C=0 after snap.

## Einstein-Hampton on +U

(4)G_mu nu = 8 pi G_4 ( T^m + T^r + T^H )_mu nu - E_mu nu

T^H_mu nu = rho_DE(0) W(b) u_mu u_nu + p_H (g_mu nu + u_mu u_nu)
W(b) = e^{-k(b-b0)} = kappa_dark^{b/b0 - 1}

Linear warp: D2 current T^y_mu, not IR vacuum e^{-4kb}.

H^2 = (8 pi G_4 / 3) (rho_m + rho_r + rho_DE(0) W(b))

## Radion

alpha = bdot/(H b) = sqrt(3 f_snap)
1 + w_H = alpha^2 / 3 = f_snap
b(z) = b0 (1+z)^{-alpha}
W(z) = kappa_dark^{(1+z)^{-alpha}-1}

Early: b->0, W->1/kappa_dark, w_eff -> -1 (5D flattening).
Late: w_eff(0)=-0.897.

Frozen-start numerical roll does not reach sigma=0 by a=1. The scaling trajectory pinned by f_snap is the solution used.

## Open

T_D2 and M_5 in GeV (k and b0 not separated). Full 5D numerics. Boltzmann C_ell.
