# triangulenes12
This repository is a part of the supplementary information of the study

_Leveraging the Bias-Variance Tradeoff in Quantum Chemistry for Accurate Negative Singlet-Triplet Gap Predictions: A Case for Double-Hybrid DFT_   
Atreyee Majumdar, Raghunathan Ramakrishnan    
[Journal of Computational Chemistry  46 (2025) e70228.](https://doi.org/10.1002/jcc.70228)


# content
- [csv_files](csv_files) contains CSV files with S<sub>1</sub>, T<sub>1</sub>, and S<sub>1</sub>-T<sub>1</sub> energies for all 12 triangular molecules calculated with different methods with `cc-pVDZ`, `cc-pVTZ`, `aug-cc-pVDZ` and `aug-cc-pVTZ` basis sets. 
- [TABLE-IV](TABLE-IV) provides a [Jupyter notebook](TABLE-IV/Scaling_methods.ipynb) and data to demonstrate linear scaling of S<sub>1</sub>-T<sub>1</sub> energies predicted with various methods (with aug-cc-pVDZ basis set) using TBE values as reference.
- [TABLE-V](TABLE-V) provides a [Jupyter notebook](TABLE-V/Corrected_Methods.ipynb) demonstrating the linear scaling of S<sub>1</sub>, T<sub>1</sub>, and S<sub>1</sub>-T<sub>1</sub> energies predicted with various methods using TBE values as reference. Various error metrics are printed.
- For all systems, minimum energy geometries at the CCSD(T)/cc-pVTZ level were used as reported in **Loos et al.** _J. Phys. Chem. Lett. 2023, 14, 49, 11069-11075_ [https://doi.org/10.1021/acs.jpclett.3c03042](https://doi.org/10.1021/acs.jpclett.3c03042). These geometries are provided in the folder [XYZ](XYZ).
