# Computer Code

> custom computer code that allows readers to reproduce the results.

### Symbolic Calculation part

#### Symbolic_Calculation_3.1.ipynb

#### Symbolic_Calculation_3.2.ipynb

#### Symbolic_Calculation_3.3.ipynb

#### Symbolic_Calculation_3.4.ipynb

* ##### Setting

  * the details are in the article and supplementary information


> Compute the expressions in the article and supplementary information. The numbers at the end of the titles, "3.X", correspond to the chapter in the SI.

* ##### Function

  * expressions: equations, solutions, ...
  * numerical computation

### Visualization & simulation part

#### Simulation_Function.ipynb

* ##### Setting

  * users can adjust the parameters of the functions as needed to obtain simulation results under different conditions
  * the simulation parameters in the article can be referred to in the captions


> Provide functions for simulation in different scenarios.

* ##### Function

  * simulation

#### Results_Visualization.ipynb

* ##### Setting

  * the data used for the bar charts and scatter plots are all contained in files "data_1.csv" and "data_2.csv".
  * the theoretical curve should be obtained by substituting the parameters into the results of the Symbolic Calculation part


> Plot some figures in the article.

* ##### Function

  * ploting

***

### Introduction

The code is organized into ipython notebooks. 

The software, module and hardware list is given below.

* Software

> Python 3.8.8 and above

* Module

| name         | version |
| ------------ | :------ |
| numpy        | 1.24.3  |
| sympy        | 1.11.1  |
| matplotlib   | 3.7.2   |
| colormaps    | 3.0.1   |
| mpl_toolkits |         |
| warnings     |         |

> If we have matplotlib installed, we would be able to import mpl_toolkits directly.

* OS

> Mac OS X, Windows, or Linux

We use Anaconda GUI to run our code (which comes with the packages automatically installed). Otherwise, we may run `pip install` with the name and version for every candidate item.

### How to Obtain the Expressions and Figures

More detailed explanations are given in the comments and markdown notes (for ipython notebooks).