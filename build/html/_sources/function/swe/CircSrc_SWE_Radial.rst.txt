.. _CircSrc_SWE_Radial:

CircSrc_SWE_Radial.m
======================================
Calculate the radial component for the ultrasound when using the SWE.

The radial component is expressed as

.. math::
   \mathcal{R}_{2\ell_i+|m_i|}(r)
   =
   \int_0^a u(r_\mathrm{s}/a)
   \mathrm{j}_{2\ell_i+|m_i|}(k_ir_{\mathrm{s},<})
   \mathrm{h}_{2\ell_i+|m_i|}(k_ir_{\mathrm{s},>})
   k_i^2 r_\mathrm{s} \mathrm{d} r_\mathrm{s}
   :label: swe_radial






