# Reproducibility Package for CCS 2026 submission \#1085: *"Finality-oriented simulation-based evaluation of blockchain consensus networks: the CNS framework"*

## Overview

The tools and scripts are currently maintained separately in three different repositories.

- [cns-engine](https://github.com/for-review-purposes/cns-engine/) contains the CNS object-oriented framework for developing 
- [cns-bitcoin](https://github.com/for-review-purposes/cns-bitcoin/) contains the cns-engine-based Nakamoto consensus implementation and attack.
- [cns-tools](https://github.com/for-review-purposes/cns-tools/) contains an R library for analyzing and visualizing data CNS.

## To Run Simulations

- Clone [cns-engine](https://github.com/for-review-purposes/cns-engine/) and [cns-bitcoin](https://github.com/for-review-purposes/cns-bitcoin/) under the same directory (so that they are sibling directories).
- Compile and install `cns-engine` in your local maven repository. Precise directions can be found in the corresponding [README](https://github.com/for-review-purposes/cns-engine/)
- Compile `cns-bitcoin` and run tests. Custom simulations can be developed and run according to the corresponding [README](https://github.com/for-review-purposes/cns-bitcoin/)


## To Reproduce Analyses

- Clone [cns-bitcoin](https://github.com/for-review-purposes/cns-bitcoin/) and [cns-tools](https://github.com/for-review-purposes/cns-tools/) under the same directory (so that they are sibling directories).
- Analysis scripts can be found under [`examples/configs`](https://github.com/for-review-purposes/cns-bitcoin/examples/configs/). 