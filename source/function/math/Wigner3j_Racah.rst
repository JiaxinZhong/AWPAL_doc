Wigner3j_Racah.m
=========================
Calculat the Wigner :math:`3j` symbol using the Racah formula.

Syntax
---------------
``w = Wigner3j_Rach(j1, j2, j3, m1, m2, m3)``.

Output arguments
------------------
``w`` --- The wigner :math:`3j` symbol given by Eq. :eq:`wigner3j`.

Input arguments
---------------

Mandatory arguments
^^^^^^^^^^^^^^^^^^^^^^^^^^
``j1_max, j2_max, j3_max`` --- The maxima of the angular momenta.

``m_1,m_2,m_3`` --- Projective quantum numbers.


Optional arguments
^^^^^^^^^^^^^^^^^^^^^^^
NA

Dependencies
---------------
NA


Notes
-------------------
- It returns wrong answers when :math:`j1, j2,j3` are very large, e.g., :math:`\sim 200`.
