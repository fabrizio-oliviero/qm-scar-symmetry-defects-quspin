# qm-scar-symmetry-defects-quspin

This repository contains the QuSpin exact diagonalization code and numerical
data associated with the manuscript

**"Symmetry protected quantum many body scars through half-gauging"**

The repository provides the numerical data and Jupyter notebooks used to
study symmetry-protected quantum many-body scars and the effects of
duality defects in one-dimensional stochastic-matrix-form (SMF) spin chains.

## Repository structure

```text
Notebooks/
├── Entanglement_Duality_Interface_k=1_chain.ipynb
├── Entanglement_k=2_chain.ipynb
├── Entanglement_k=3_chain.ipynb
└── LoschmidtEcho_k1_chain.ipynb

data/k3/
├── quspin_simulation_data_k3_chain_1_defects.npz
└── quspin_simulation_data_k3_chain_None_defects.npz

datak2/
├── quspin_simulation_data_k2_chain_1_defects.npz
└── quspin_simulation_data_k2_chain_2_defects.npz

README.md
│
└── README.md
