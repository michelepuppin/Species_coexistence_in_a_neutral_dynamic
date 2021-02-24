In this project I study the paper "Species coexistence in a neutral dynamic with environmental noise" authored by Jorge Hidalgo, Samir Suweis and Amos Maritan. In this paper they study the impact of environmental variability on the biodiversity of an ecosystem, which has proved to have important consequences in the organization of ecological communities. In particular, they analyze how environmental noise affects mean time of coexistence, in the framework of Neutral Theory. To do that, they consider a model with two species competing for resources where environment conditions affect species fitness in two ways: a linear fitness case and a relative fitness case. Specifically, they study a Voter Model dynamic in a well-mixed population, both analytically and numerically. They find that, with environmental fluctuations, the mean time of coexistence is always reduced in the case of linear fitness, while it can be increased or reduced based on the correlation time of the environment, in the case of relative fitness.

I implement a Python code to reproduce the numerical simulations performed in the paper, both for the linear fitness case and the relative fitness case, with a particular attention to code optimization. Moreover, I drop the assumption of a well-mixed population and I study numerically an analogous model in order to consider spacial effects in the relative fitness case. I analyze the mean coexistence time running the dynamics on 2D square lattice, random networks (Erdos-Renji), scale free networks (Bararabsi-Albert) and small world networks (Watts-Strogatz). Analyzing the results, I find no significative differences among different types of network. Furthermore, I find again that mean time of coexistence can be increased or reduced based on the correlation time of the environment, but the threshold seems to differ with repsect to the well-mixed population model.


Contents:

1_Well_Mixed.ipynb: Numerical simulation of the Voter Model in well-mixed assumptions both for linear fitness case and for relative fitness case

2_Spatial_Effects.ipynb: Numerical simulation of the Voter Model considering spacial effects for the relative fitness case
Plots.ipynb: Jupyter Notebook to produce plots

Sim_A: Folder with simulation results for Voter Model with well-mixed population assumption

Sim_Latt: Folder with simulation results for Voter Model on 2D square lattice

Sim_ER: Folder with simulation results for Voter Model on Erdos-Renji networks

Sim_SF: Folder with simulation results for Voter Model on scale free networks

Sim_WS: Folder with simulation results for Voter Model on small world networks

images: Folder with plots
