BesselJ.m
=============================

Calculate the Bessel function of the first kind
:math:`J_m(z)`.

Syntax
-------------------------
``J = BesselJ(m, z, varargin)``

Input arguments
-----------------------------------

Mandatory arguments
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
- ``m`` 
  
  - The order :math:`m\in \mathbb{Z}`

- ``z`` 

  - The argument :math:`z`
    



Optional arguments
^^^^^^^^^^^^^^^^^^^^^^^^^^^
- ``'is_log' = false`` 

  - ``true`` --- Return the logarithm of the result, i.e., :math:`\ln J_m(z)`

- ``'nu0' = 0``

  - Return :math:`J_{m+\nu_0}(z)`
  - :math:`0 < \nu_0 < 1`
