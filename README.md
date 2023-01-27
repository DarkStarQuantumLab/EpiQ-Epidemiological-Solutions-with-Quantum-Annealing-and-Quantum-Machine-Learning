# Epidemiological Solutions with Quantum Annealing


## Installation

For a local installation, ideally in a virtual environment, run:

    pip install -r requirements.txt

## Epidemiological Models Supported

The following [epidemiological models](https://en.wikipedia.org/wiki/Compartmental_models_in_epidemiology)are available:
Markup : - SIR
         - SIRD
         - SEIR
         - SEIRD
         - SEIivlcvRDVIm

## Lockdown Management (Knapsack Problem)

The recommendation upon which a cities is recommended for lockdown is given by the solution of [the knapsack problem](https://en.wikipedia.org/wiki/Knapsack_problem). The algorithm takes into the consideration such parameters as the number of population in the city, the number of infected population, GDP of the city, the number of available places in hospitals. 
The knapsack could be solved on a classical computer (CPU), on the physical quantum hardware (QPU) available via [DWave Leap cloud services](https://www.dwavesys.com/solutions-and-products/cloud-platform/), or as the simulated annealing algorithm. 

An example the lockdown recommendation is depicted below.
| City/ Days Elapsed |  0     | 5      |   10   |
|--------------------|--------|--------|--------|
| ``city 1``         | open   | closed |closed  |
| ``city 2``         | open   | closed |closed  |
| ``city 3``         | open   | closed |closed  |


## QSVM (Quantum Support Vector Machine)

The QSVM makes predictions infected/uninfected based on the symptomes and patient's age.

The QSVM could be executed on a physical quantum annealing device or as the simulated annealing algorithm locally. 

## License

This work is licensed under the [Apache 2 License](https://www.apache.org/licenses/LICENSE-2.0) and is owned by [DarkStarQuantumLab, Inc.](https://github.com/DarkStarQuantumLab). 
