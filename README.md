TTTT_conformal_blocks
=====================

The [Mathematica](https://www.wolfram.com/mathematica/) notebook `TTTT_conformal_blocks.nb` computes conformal blocks for the 4-point correlation function of energy-momentum tensors in momentum space, in the massless and forward limits, projected onto transverse polarizations, and working in arbitrary space-time dimension.

The results include conformal blocks for all operators in the T x T OPE that have up to 4 Lorentz indices. Using the Young diagram notation in which `(n)` indicates a n-index symmetric traceless tensor, and indicating the number of tensor structures (or correspondingly OPE coefficients), the non-zero conformal blocks are:
- a scalar operator, with 1 structure
- a 2-index symmetric operator `(2)` with 2 structures
- a 3-index antisymmetric operator `(1,1,1)` with 1 structure
- a 3-index mixed-symmetry operator `(2,1)` with 1 structure
- a 4-index symmetric operator `(4)` with 3 structures
- a 4-index mixed-symmetry operator `(2,2)` with 2 structures

Moreover, the notebook also verifies that the conformal blocks for all other operators vanish. These are operators of the type `(1)`, `(1,1)`, `(3)`, `(3,1)`, `(2,1,1)`, and `(1,1,1,1)`.

The computation of all conformal blocks involves heavy computer algebra and can take significant time to run (about 20 minutes on a standard laptop).

This work is part of a on-going project in collaboration with Xiaochuan Lu and Markus Luty. A publication is in preparation and will soon be freely available at [arxiv.org](https://arxiv.org/).

