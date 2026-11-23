The S-coordinate stretching ``CSF`` (``src/set_scoord_mod.F90``) is evaluated without cancellation, so ``Cs_r`` and ``Cs_w`` are accurate to about 1e-15 for every ``theta_s`` and ``theta_b``, and outputs change at roundoff.
- For ``theta_s >= 0.5`` with ``theta_b = 0`` or ``theta_b >= 0.1`` the stretching changes by at most 8e-15.
