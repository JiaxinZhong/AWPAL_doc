HankelH_Asym.m
=========================

Calculate the Hankel function :math:`H_m(z)` using the asymptotic method.

See Eq. (10.17.5) in :cite:t:`Olver2019NISTDigitalLibrary`.

Syntax
---------------
``H = HankelH_Asym(m, z)``

Output arguments
------------------
- **H** --- :math:`\ln H_m(z)`

Input arguments
---------------
- **m** --- order
- **z** --- the argument :math:`z`

:eq:`Hm1`

.. math:: e^{i\pi} + 1 = 0
   :label: euler

.. math::
   H_m^{(1)}(z) 
   \sim \sqrt{\frac{2}{\mathrm{i}\pi z}} 
   \frac{\mathrm{e}^{\mathrm{i}z}}{\mathrm{i}^m}
   :label: Hm1


Dependencies
---------------
NA

References
--------------------
.. bibliography::

