# Power Grid Optimization with Pyomo 

This project is a smart approach to network flow and cost minimization
Welcome to Power Grid Optimization, a Python-based energy management model designed to optimize power generation, transmission, and cost efficiency in a microgrid system.  This project leverages Pyomo, NetworkX, and Matplotlib to simulate power flow, enforce grid constraints, and minimize operational costs.

# Project Overview
This optimization model represents a small-scale power grid using a directed graph where nodes are buses and edges are power transmission lines. The objective? Ensure power balance while minimizing generation costs and import/export expenses.

 # Key Features
Graph-based Power Network: Uses NetworkX to model power buses and transmission lines,
Optimization with Pyomo: Implements power flow constraints and economic dispatch,
Cost Function: Considers generation cost, import/export cost, and transfer limits,
Line Flow Limits: Keeps power flow within safe ratings,
Power Balance: Maintains supply-demand equilibrium at each bus,
Generator Constraints: Ensures generation stays within min-max limits

# Visualization: Plots the network structure & optimized power flow
# How It Works <br>
1 Define the Network:<br>

Nodes (Buses) represent locations in the power grid
Edges (Lines) represent transmission paths with power limits<br>
2️ Introduce Generators:

Define generation capabilities & cost functions<br>
3️ Optimize Power Flow:

Minimize total cost while meeting demand
Ensure grid stability with power conservation constraints<br>
4️ Solve & Visualize:

Results & Visualization are shown below in the graph
Once solved, the model provides:<br>
📌 Total Cost Breakdown (Generation + Import/Export Costs) = 208.400 <br>
📌 Power Generated at Each Bus = 0.14<br>
📌 Power Flow on Each Transmission Line = 0.03257<br>

![output graph](https://github.com/user-attachments/assets/ee9ec7c2-5352-4396-a6d2-f0ed8fec8ea7)



