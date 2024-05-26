# Stone's Blind Source Separation Algorithm

Simple (and I mean simple - it's just one file with a single class) implementation of Stone's BSS algorithm. Heavily inspired by Dr. Stone's [MATLAB Implementation](https://jamesstone.sites.sheffield.ac.uk/code).

# Usage
Instantiate the `StoneBSS` class and pass the relevant hyperparameters. Then, call the `.fit()` method with the mixed signals as an argument. The `StoneBSS` instance can then be called like a function to unmix a given signal. Example usage can be found in `stone_bss.py`

# References
```bibtex
@article{article,
author = {Stone, James},
year = {2001},
month = {08},
pages = {1559-74},
title = {Blind Source Separation Using Temporal Predictability},
volume = {13},
journal = {Neural computation},
doi = {10.1162/089976601750265009}
}
```
