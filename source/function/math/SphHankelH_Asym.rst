SphHankelH_Asym.m
=========================

Calculate the spherical Hankel function :math:`\mathrm{h}_n(z)` using the asymptotic expansion.

Syntax
---------------
``h = SphHankelH_Asym(n, z)``

Output arguments
------------------
``h`` --- :math:`\mathrm{h}_n(z)`.

Input arguments
---------------
Mandatory arguments
^^^^^^^^^^^^^^^^^^^^^^^^^^
``n`` --- order

``z`` --- the argument :math:`z`


Optional arguments
^^^^^^^^^^^^^^^^^^^^^^^
``approx_order``

- :math:`K\in \mathbb{N}` --- Calculate the spherical Hankel function using the asymptotic expansion.

- ``0`` --- The returned result reduces to Eq. :eq:`hn23`, see Eq. (10.52.4) in :cite:t:`Olver2019NISTDigitalLibrary`.

.. math::
   \mathrm{h}_n^{(1)}(z)
   \sim 
   \frac{\mathrm{e}^{\mathrm{i}z}}{\mathrm{i}^{n+1}z}
   :label: hn23

Dependencies
---------------
The result is obtained by calculating the Hankel function using :ref:`HankelH_Asym_m` with the relation by, see Eq. (10.47.5) in :cite:t:`Olver2019NISTDigitalLibrary`.

.. math::
   \mathrm{h}_n^{(1)}(z)
   = 
   \sqrt{\frac{\pi}{2z}}
   H_{n+1/2}^{(1)}(z)



