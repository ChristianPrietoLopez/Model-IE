# MCMC – Parameter Estimation for the Iterated Energy Model (IE)

This module performs a Markov Chain Monte Carlo (MCMC) parameter estimation for the Iterated Energy (IE) cosmological model.

## Structure
- `mcmc_IE.py`: Main script that defines the model, the likelihood function and runs the MCMC sampler.
- `data/pantheon_mini.csv`: Miniature dataset based on Pantheon+ for testing.
- `results/`: Stores corner plots and trace plots.
- `ajuste_IE.ipynb`: Jupyter Notebook to visualize and interact with the fitting process.
- `requirements.txt`: List of required Python packages.

## How to run

You can run this module locally or via Binder:

### Locally
```bash
pip install -r requirements.txt
python mcmc_IE.py
```

### Binder (online)
[Launch in Binder](https://mybinder.org)

## Contact
Developed by Christian Prieto López, 2025.
