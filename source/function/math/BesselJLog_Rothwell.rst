BesselJLog_Rothwell.m
=========================

Calculate the log of the spherical Bessel function :math:`J_n(z)` using the method proposed in :cite:t:`Rothwell2008ComputationLogarithmBessel`.

Syntax
---------------
``[J, J_prime] = BesselJLog_Rothwell(N, z)``

Output arguments
------------------
- **J** --- :math:`\ln J_n(z)`
- **J_prime** --- :math:`\ln J_n'(z)`

Input arguments
---------------
- **N** --- maximal order
- **z** --- the argument :math:`z`

Dependencies
---------------
- ``ContFracLentz.m``


