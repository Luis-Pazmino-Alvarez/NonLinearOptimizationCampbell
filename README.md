# NonLinearOptimizationCampbell
This project models and solves a nonlinear optimization problem using Pyomo in Python, focusing on maximizing profits for a car dealership named Campbell Motors. The business scenario involves determining the optimal pricing strategy for trucks and wagons, considering labor constraints and price-sensitive demand functions.

Problem Description
Campbell Motors wants to:

Maximize total profit from the sale of trucks and wagons.

Respect a limited labor capacity of 250 hours.

Incorporate nonlinear demand curves that relate price to expected demand for each vehicle type.

The project uses the following:

Nonlinear price-demand equations:

Truck Demand = 500 − 17 × (TruckPrice / 1,000)

Wagon Demand = 400 − 12 × (WagonPrice / 1,000)

Cost of goods:

Truck = $20,000

Wagon = $25,000

Labor usage:

Truck = 3 hours

Wagon = 2 hours

Tools Used
Pyomo

IPOPT solver

Google Colab environment (with dynamic installation of missing packages)

Optimal Solution
Truck Price: $26,049

Wagon Price: $30,062

Maximum Profit: $544,505

How to Run
Open the notebook in Google Colab or Jupyter.

Ensure pyomo and ipopt are installed (automatically handled in Colab).

Execute cells sequentially.

