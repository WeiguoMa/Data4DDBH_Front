# Data4DDBH_Front

Source data for *Dissipation-Selected Resonant Fronts in a Driven-Dissipative Bose-Hubbard Lattice*.

Each ZIP contains CSV tables. File letters match figure panels. Values are unscaled unless stated below. Figure captions and Methods define the calculations.

| File | Data |
| --- | --- |
| [Fig1.zip](Fig1.zip) | Front formation, panel b. Panel a is a schematic. |
| [Fig2.zip](Fig2.zip) | Density, transverse spectra and particle-number dynamics. |
| [Fig3.zip](Fig3.zip) | Center-of-mass maps and particle-number cuts. |
| [Fig4.zip](Fig4.zip) | Nonzero transverse-momentum fraction. |
| [S1.zip](S1.zip) | Exact and TWA dimer densities. |
| [S2.zip](S2.zip) | Uniform-loss density maps. |
| [S3.zip](S3.zip) | Theoretical and TWA pinned profiles. |
| [S4.zip](S4.zip) | Discrete modes and Airy envelopes. |
| [S5.zip](S5.zip) | Transverse growth rates. |
| [S6.zip](S6.zip) | Lyapunov estimates and localized-state growth rates. |
| [S7.zip](S7.zip) | Particle-number staircases. |
| [S8.zip](S8.zip) | Stationary branches, fold and density rearrangement. |
| [S9.zip](S9.zip) | Boundary-condition comparison. |
| [S10.zip](S10.zip) | System-size comparison. |
| [S11.zip](S11.zip) | Spatial intensity switching. |

## Labels

- `x`, `y`, `m`: lattice coordinates and transverse-mode index.
- `t`: simulation time in units of `1/J`; in S11, time after preparation. These are physical time coordinates, not recording dates.
- `F`, `gamma`: detuning and loss gradients in units of `J`.
- `n`: density; `N`: total particle number; `COM`: center of mass along x.
- `SE`: standard error of the corresponding estimate; `f` in Fig4: nonzero transverse-momentum fraction.
- `P` in Fig2: one-sided transverse density power; `growth`, `lambda`: rates in units of `J`.
- `theory`, `TWA`, `exact`: values from the indicated method. These are density in S1/S3 and particle number in S7.
- `BC`, `Lx`, `Ly`: boundary condition along x and lattice dimensions.
- S4: `s=(x-xt)/ell`, `n` is normalized mode density, and `mu`, `epsilon`, `xt`, `ell` specify the mode and its Airy envelope.
- S8: `lower`, `upper`, `fold` label stationary solutions; `twa` labels ensemble estimates.
- S11: `fixed` and `linear` are the reference densities; `off` and `on` are the averaged profiles.

S1 panels a–d use `(F,x0)=(0.31,0),(0.49,0),(0.425,1),(0.425,4)`; `site=0,1` labels the two sites. The plotted S1 uncertainty band is `1.998 SE`; other plotted uncertainty bands are `1 SE`. S6 panel a averages growth from `t=300` to each listed time; panel b uses `F=0.49`. Full longitudinal profiles are retained in S8–S10 even where the figures show a smaller range.
