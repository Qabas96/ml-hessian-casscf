# ML Approximation of Hessian Components for CASSCF

**Capstone Project** – Cyber Training 2026

Machine Learning model to predict the CI Hessian diagonal in CASSCF(6,6) calculations as a proof-of-concept toward faster second-order methods and Resonating Hartree-Fock.

## Project Status
- Data generated for 10+ molecules with def2-SVP
- Feature engineering completed
- Neural Network trained (PyTorch)
- Physics-Informed approach in progress

## Repository Structure
- `notebooks/` – All analysis notebooks
- `data/` – Raw and processed datasets
- `results/` – Models and plots
- `src/` – Reusable Python code

## How to Reproduce
```bash
pip install -r requirements.txt
jupyter notebook
