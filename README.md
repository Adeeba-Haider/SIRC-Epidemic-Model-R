SIRC Model in R
This repository contains the implementation of the SIRC (Susceptible-Infected-Recovered-Cross-immuned) model in R. The SIRC model is a mathematical framework used to simulate the spread of infectious diseases within a population.

Description
The code in this repository includes the necessary functions and equations to simulate the dynamics of an epidemic using the SIRC model. It takes into account parameters such as the infectious population's recovery rate, the rate at which the cross-immune population reverts to being susceptible, every compartment's mortality rate is equal to the population's infant mortality rate, and the rate at which the recovered population develops cross-immunity.

Features
Numerical solver to compute the solution of the SIRC model equations
Plots showing the changes in the number of susceptible, infected, recovered, and cross-immuned cases over time
Usage
Make sure you have R and the deSolve package installed on your machine.
Clone or download this repository.
Set the working directory to the location of the repository.
Run the sirc_model.R script to execute the SIRC model simulation.
Adjust the model parameters and initial conditions as needed.
Observe the generated plots to analyze the epidemic dynamics.
Contributions
Contributions to enhance the functionality or optimize the code are welcome. If you find any issues or have suggestions, please feel free to open an issue or submit a pull request.
