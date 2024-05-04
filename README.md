# BASILISK 0.1a

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

1. Clone the repository: `git clone https://github.com/makki547/basilisk.git`
2. Install the package: `cd basilisk; pip install .`

Clone this repository by `git clone https://github.com/makki547/basilisk.git` and run `pip install .` in the cloned repository directory.

## Changes from the Original Codes

The original codebase was written in Python 2.x. It has been ported to Python 3 using the `2to3` tool, with additional manual adjustments made to resolve compatibility issues.
