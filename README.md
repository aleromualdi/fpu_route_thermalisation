# The Fermi-Pasta-Ulam-Tsingou system and its route to thermalization

This repository implements a deep learning methodology employing a Long Short-Term Memory (LSTM)-based autoencoder model to explore the lifespan of metastable states im the Fermi-Pasta-Ulam (FPU) system and, consequently, identify the phase transition leading to equipartition.

More info in `notebooks/route_to_thermalization.ipynb`.

## Installation

The code runs on Python 3.9

To install requirements:

```
pip install -r requirements.txt
```

## Generate input data
 
The input trajectory data for the FPU system are generated by an integrator based on Verlet algorithm. To generate the input dataset, consisting on a single trajectory for the non-linear parameter $\beta = 1.8$ run the script:

```
 python scripts/generate_input_data.py <args>
```



