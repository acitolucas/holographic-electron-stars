# Files description

Wolfram Mathematica 14.2 codes for computing holographic electron star profiles and their stability/thermodynamic analysis presented in [arXiv:2602.10460](https://doi.org/10.48550/arXiv.2602.10460). These numerical computations are divided into two different notebooks:

- `Star_profiles.nb`: This file computes the mass, charge, and energy density of the electron star. The physical parameters can be modified, and the notebook is organized to provide a quick way to compute a test star profile with all physical parameters fixed. Then, by inputting a range for the central chemical potential or temperature, it computes all the profiles and organizes the results into a Katz plot. Moreover, it calculates the free energy of the star and compares it with the black hole and thermal AdS free energies. Lastly, it includes a separate module that handles the $T=0$ case.
- `Star_analysis.nb`: This notebook collects the data obtained from multiple runs of the previous file, varying the thermodynamic variables and other physical parameters. It demonstrates the procedure to construct the correct Katz plot for the stability analysis, i.e. fixing the ratio $\mu/T$ using boundary values rather than the central values obtained in the other notebook. Analogously, it computes the correct free energy diagram in the Grand Canonical ensemble (where the boundary chemical potential is fixed) to analyze the first-order phase transition. Finally, it includes additional results shown in the paper, such as the maximum physical parameters required to allow a Star-BH phase transition and the maximum possible quantum critical point.

## Contributing & Feedback

This repository is a static archive hosting the numerical codes used in the paper. While direct modifications to this main branch are restricted, feedback, bug reports, or questions are highly welcome!

Please feel free to open an **Issue** or contact me via email if you find any typos or unexpected behavior in the notebooks.
