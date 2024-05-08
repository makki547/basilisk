# BASILISK

This project was originally developed by Tim Harder and Jes Frellsen and has been forked from [SourceForge](https://sourceforge.net/projects/basilisk-dbn/).

**Original Repository Description:**
> BASILISK is a probabilistic model that explores the conformational space of amino acid side chains in proteins. Unlike traditional rotamer libraries, BASILISK models the chi angles continuously, accounting for the influence of the protein's backbone.
> 
> **Features:**
> - Continuous rotamer library
> - Side chain angular space
> - Python implementation with Mocapy
> - Continuous dependence on backbone
> - Dynamic Bayesian Network (DBN)
> - Von Mises distribution

## How to Install

0. (Prerequisite) Install Numpy and Biopython in an appropriate way, for example via `pip install numpy biopython`
1. Clone the repository: `git clone https://github.com/makki547/basilisk.git`
2. Install the package via pip: `cd basilisk; pip install .`


## Changes from the Original Codes

The original codebase was written in Python 2.x. It has been ported to Python 3 using the `2to3` tool, with additional manual adjustments made to resolve compatibility issues.

## Citation

Please cite the following paper if you publish papers using the BASILISK:

>Harder, T., Boomsma, W., Paluszewski, M. et al. Beyond rotamers: a generative, probabilistic model of side chains in proteins. BMC Bioinformatics 11, 306 (2010). [https://doi.org/10.1186/1471-2105-11-306](https://doi.org/10.1186/1471-2105-11-306)
