CheckDim.m
=============================

Validate the dimensions of input arguments.

Syntax
-------------------------
``res = CheckDim(type, arg1, arg2, ...)``

Input arguments
-----------------------------------
- ``type`` --- the type of the validation
  
  - Value ``'preceeding'`` --- Suppose the dimensions of the first argument is :math:`a_1\times a_2\times \cdots \times a_n`, then those of the second argument must be :math:`1\times 1 \times \cdots \times 1 \times b_1 \times b_2 \times \cdots \times b_m`.
    The preceeding :math:`n` dimensions of the second argument must be 1.

- ``arg1, arg, ...`` --- There can be arbitrary number of input arguments


Output arguments
----------------------------
- ``res`` --- ``true`` if validated.

