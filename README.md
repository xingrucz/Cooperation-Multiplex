# Computer Code

This repository contains custom code developed to reproduce all analytical and numerical results presented in the main text and the supplementary information (SI).

The codebase is organized into several Jupyter (IPython) notebooks, corresponding to symbolic calculations, simulations, and figure generation.

---

## Symbolic Calculation

The following notebooks perform symbolic derivations and analytical computations appearing in the main text and the SI. The numbering "3X" corresponds to the relevant section numbers in the SI.

### Notebooks

- `Symbolic_Calculation_3.1.ipynb`

- `Symbolic_Calculation_3.2.ipynb`

- `Symbolic_Calculation_3.3.ipynb`

- `Symbolic_Calculation_3.4.ipynb`

### Settings

All model assumptions, parameters, and derivations are described in detail in the main text and the SI.

### Functionality

- Symbolic derivation of analytical expressions
- Solving equations and simplifying results
- Auxiliary numerical evaluation of symbolic expressions


## Simulation and Visualization

### Notebooks

- `Simulation.ipynb`
- `Results_Visualization.ipynb`

### Setting

Users can freely adjust model parameters to explore simulation outcomes under different conditions. Parameter values used in the main text and the SI are specified in the corresponding figure captions.

Data used for bar charts and scatter plots are stored in:
- `data_1.csv`
- `data_2.csv`

Theoretical curves are obtained by substituting parameters into the analytical expressions derived in the *Symbolic Calculation* notebooks.

### Functionality

- Agent-based simulations under different evolutionary scenarios
- Visualization of theoretical and simulation results
- Generation of figures appearing in the paper

---

## Software Environment

### Programming Language

Python 3.8.8 or later

### Required Packages

| name         | version |
| ------------ | :------ |
| numpy        | 1.24.3  |
| sympy        | 1.11.1  |
| matplotlib   | 3.7.2   |
| colormaps    | 3.0.1   |
| mpl_toolkits |         |
| warnings     |         |

> Note: `mpl_toolkits` is included with `matplotlib` and does not require separate installation

### Operating Systems
- macOS
- Windows
- Linux

We recommend running the code using **Anaconda**, which automatically manages the required packages. Alternatively, packages can be installed manually via `pip` using the versions listed above.

---

## Reproducing the Results

More detailed explanations are provided directly in the code through inline comments and Markdown cells within each Jupyter notebook. By following the notebooks in sequence, users can reproduce all analytical expressions, simulations, and figures reported in the paper.

