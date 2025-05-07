# Energy System Modeling Project

This repository contains the code and data for our energy system modelling project using PyPSA in Python. The analysis is conducted in Jupyter notebooks.

## Repository Structure

- **Project.ipynb** – Main notebook with all components of the analysis (excluding Part C).
- **Project_Part_C.ipynb** – Contains Part C of the project.
- **Data/** – Folder containing all datasets used in the project (e.g., electricity demand, wind profile, etc.).

> ⚠️ Make sure the `Data` folder is located in the same directory as the notebooks. The notebooks access data using relative paths (e.g., `"Data/electricity_demand.csv"`).

## Dependencies

To run the notebooks, you’ll need the following Python packages:

- Python 3.8+
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- pypsa
- gurobipy (optional, for using Gurobi solver)

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
2. Launch Jupyter Notebook
3. Open files and run all cells in order. The notebooks will load the required data and execute the model setup and optimization steps.

