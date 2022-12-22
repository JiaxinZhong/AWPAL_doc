SphHankelH.m
=============================

Calculate the spherical Hankel function :math:`\mathrm{h}_n(z)`.

Syntax
-------------------------
``[h, h_prime] = SphHankelH(n, z, varargin)``

Input arguments
-----------------------------------

Mandatory arguments
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
``n`` 
  
- The order :math:`n\in \mathbb{Z}`


``z`` 

- The argument :math:`z`


Optional arguments
^^^^^^^^^^^^^^^^^^^^^^^^^^^
``'is_log' = false`` 

- ``true`` --- Return the logarithm of the result, i.e., :math:`\ln h_m(z)`

``'kind' = 1``

- ``1`` -- Return the spherical Hankel function of first kind
- ``2`` -- Return the spherical Hankel function of second kind

``'arg_is_large' = false``

- ``true`` -- Evaluate the function using the limiting form as shown by Eq. :eq:`hn23`.
