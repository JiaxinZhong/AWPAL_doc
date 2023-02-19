Wigner3j.m
=========================
Calculat the Wigner :math:`3j` symbol using precalculated tables.

Syntax
---------------
``w = Wigner3j(j1_max, j2_max, j3_max, m1, m2, m3)``.

Output arguments
------------------
``w`` --- The wigner :math:`3j` symbol, which reads 

.. math::
   \begin{pmatrix}
   2j_1 + |m_1| & 2j_2 + |m_2| & 2j_3 + |m_3| \\
   m_1 & m_2 & m_3
   \end{pmatrix}
   :label: wigner3j

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

