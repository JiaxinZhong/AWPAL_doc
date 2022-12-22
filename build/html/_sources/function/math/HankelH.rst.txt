HankelH.m
=============================

Calculate the Hankel function 
:math:`H_m(z)`.

Syntax
-------------------------
``[H, H_prime] = HankelH(m, z, varargin)``

Input arguments
-----------------------------------

Mandatory arguments
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
``m`` 
  
- The order :math:`m\in \mathbb{Z}`


``z`` 

- The argument :math:`z`


Optional arguments
^^^^^^^^^^^^^^^^^^^^^^^^^^^
``'is_log' = false`` 

- ``true`` --- Return the logarithm of the result, i.e., :math:`\ln H_m(z)`

``'nu0' = 0``

- Return :math:`H_{m+\nu_0}(z)`
- :math:`0 < \nu_0 < 1`

``'kind' = 1``

- ``1`` -- Return the Hankel function of first kind
- ``2`` -- Return the Hankel function of second kind

``'arg_is_large' = false``

- ``true`` -- Evaluate the function using the limiting form as shown by Eq. :eq:`Hm1`
