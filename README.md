# qm-scar-symmetry-defects-quspin

This repository contains the QuSpin exact diagonalization code and numerical
data associated with the manuscript

**"Symmetry protected quantum many body scars through half-gauging"**

The repository provides the numerical data and Jupyter notebooks used to
study symmetry-protected quantum many-body scars and the effects of
duality defects in one-dimensional stochastic-matrix-form (SMF) spin chains.

## Repository structure

### `Notebooks/`

This directory contains the Jupyter notebooks used for the numerical
calculations and analysis:

- `Entanglement_Duality_Interface_k=1_chain.ipynb`
- `Entanglement_k=2_chain.ipynb`
- `Entanglement_k=3_chain.ipynb`
- `LoschmidtEcho_k1_chain.ipynb`

The notebooks use exact diagonalization with QuSpin.

### `datak3/`

This directory contains numerical data generated from the exact
diagonalization calculations.

The datasets include eigenenergies and entanglement entropies, together with
the parameters used in the corresponding calculations.

### `datak2/`

This directory contains the numerical data for the $k=2$ calculations.

## Requirements

The calculations require:

- Python 3
- QuSpin
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook

The relevant model parameters and numerical details are specified in the
corresponding notebooks.

## Reproducibility

The notebooks and numerical data provided in this repository are intended to
facilitate reproduction of the numerical results presented in the associated
manuscript.

The numerical datasets are provided separately from the notebooks so that the
analysis can be performed without repeating the exact diagonalization
calculations.

## Citation

If you use the code or data from this repository, please cite the associated
manuscript.

The DOI for the archived version of this repository will be added here after
the repository is released through Zenodo.

## License

To be added.
