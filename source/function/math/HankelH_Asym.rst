.. _HankelH_Asym_m:

HankelH_Asym.m
=========================

Calculate the Hankel function :math:`H_m(z)` using the asymptotic method.

Syntax
---------------
``H = HankelH_Asym(m, z)``

Output arguments
------------------
``H`` --- :math:`H_m(z)`.

Input arguments
---------------
Mandatory arguments
^^^^^^^^^^^^^^^^^^^^^^^^^^
``m`` --- order

``z`` --- the argument :math:`z`


Optional arguments
^^^^^^^^^^^^^^^^^^^^^^^
``approx_order``

- :math:`K\in \mathbb{N}` --- Calculate the Hankel function using the asymptotic expansion given by Eq. :eq:`H90239rj2309`, see Eq. (10.17.5) in :cite:t:`Olver2019NISTDigitalLibrary`.

.. math::
   H_m^{(1)}(z)
   \sim
   \sqrt{\frac{2}{\pi z}}
   \mathrm{e}^{-\mathrm{i}\omega}
   \sum_{k=0}^K \mathrm{i}^k 
   \frac{a_k(m)}{z^k}
   :label: H90239rj2309

- ``0`` --- The returned result reduces to Eq. :eq:`Hm1`, see Eq. (10.2.5) in :cite:t:`Olver2019NISTDigitalLibrary`.

.. math::
   H_m^{(1)}(z) 
   \sim \sqrt{\frac{2}{\mathrm{i}\pi z}} 
   \frac{\mathrm{e}^{\mathrm{i}z}}{\mathrm{i}^m}
   :label: Hm1


Dependencies
---------------
NA


