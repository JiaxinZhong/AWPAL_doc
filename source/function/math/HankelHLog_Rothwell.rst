HankelHLog_Rothwell.m
=========================

Calculate the log of the spherical Hankel function :math:`H_m(z)` using the method proposed by Rothwell 2018.

Syntax
---------------
``[H, H_prime] = HankelJLog_Rothwell(M, z)``

Output arguments
------------------
- **H** --- :math:`\ln H_m(z)`
- **H_prime** --- :math:`\ln H_m'(z)`
   - Option **is_cal_derivative** must be `true`.

Input arguments
---------------
- **M** --- maximal order
- **z** --- the argument :math:`z`

Dependencies
---------------
- ``ContFracLentz.m``

