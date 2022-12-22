Template.m
=========================
Here describe the purpose of this function.

Syntax
---------------
The syntax to call this function, e.g.,
``h = SphHankelH_Asym(n, z, varargin)``.

Output arguments
------------------
Output arguments of this function, e.g.,
``h`` --- :math:`\mathrm{h}_n(z)`.

Input arguments
---------------
Input arguments of this function.

Mandatory arguments
^^^^^^^^^^^^^^^^^^^^^^^^^^
Mandatory input arguments, e.g., 

``n`` --- order

``z`` --- the argument :math:`z`


Optional arguments
^^^^^^^^^^^^^^^^^^^^^^^
Optional input arguments which are included in ``varargin``, e.g.,
``approx_order``

- :math:`K\in \mathbb{N}` --- Calculate the spherical Hankel function using the asymptotic expansion.

Dependencies
---------------
The functions required in this function. 
Below is an example.

The result is obtained by calculating the Hankel function using :ref:`HankelH_Asym_m` with the relation by, see Eq. (10.47.5) in :cite:t:`Olver2019NISTDigitalLibrary`.

.. math::
   \mathrm{h}_n^{(1)}(z)
   = 
   \sqrt{\frac{\pi}{2z}}
   H_{n+1/2}^{(1)}(z)



