# Cobaya Tutorials

Welcome to the **Cobaya Tutorials** repository! This repository contains a series of tutorials in the form of `jupyter notebooks` designed to help users understand how cosmological inference works and effectively learn and use [Cobaya](https://pypi.org/project/cobaya/) (Cosmological Bayesian Analysis), a powerful tool for cosmological parameter estimation and model testing.

## Overview

`Cobaya` is a Python-based framework for cosmological parameter estimation and model comparison. These tutorials provide step-by-step guidance on using Cobaya to perform various types of cosmological analyses. Whether you're new to cosmological analysis or looking to refine your skills with `Cobaya`, these tutorials will help you keeping your skills up to date.

## Exercises

- **Tutorial 1**: It contains two exercises about (1) how to sample a multi-variate Gaussian and Ring likelihood distributions, and (2) how to run simple cosmology chains.
- **Tutorial 2**: It teaches the user how to use the `get_model()` wrapper of `Cobaya` to retrieve all internal calculations and requirements without hacking the source code.

## Installation

- **Clone the Repository**:
  
   ```bash
   git clone https://github.com/gcanasherrera/cobaya-tutorials.git
   cd cobaya-tutorials
   ```


- **Requirements**:
  
  `python`, latest `Cobaya` version and its cosmology dependencies.
  We recommend running the notebooks in [Google Colab](http://colab.research.google.com), and get `Cobaya` and dependencies installed in the cloud by adding in the first cells:
   ```bash
   !pip install cobaya
   !cobaya-install cosmo -p .
   ```

## Contributing
If you would like to contribute, follow the steps below:

1. Open an issue to let the `cloelite` maintainers know about your contribution plans
2. Fork the repository
3. Create a new branch:
   ```sh
   git checkout -b feature/your-feature-name
   ```
4. Commit your changes:
   ```sh
   git commit -m 'Add some feature'
   ```
5. Push to the branch:
   ```sh
   git push origin feature/your-feature-name
   ```
6. Open a pull request

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author
(Dr. Guadalupe Cañas-Herrera)[https://github.com/gcanasherrera].
