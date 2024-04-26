# Organic Food Supply Chain Optimization for Produce Distribution

## Project Overview
This project presents an optimization model for a produce company that specializes in the distribution of organically grown apples. The company aims to devise a cost-effective strategy for transporting apples from its orchard to preparation centers and then to four regional specialty stores.

## Data Summary
The transportation and preparation cost structure, capacity of preparation centers, and the demand at specialty stores are as follows:

### Cost Structure
- Transportation cost from orchard to preparation centers (per pound)
- Preparation cost at centers (per pound)
- Shipping cost from centers to stores (per pound)

### Capacity and Demand
- Monthly capacities at each of the three preparation centers (in pounds)
- Monthly demand at each of the four specialty stores (in pounds)

## Objective
The primary objective is to minimize the total cost associated with the transportation and preparation of the organic apples, subject to capacity and demand constraints.

## Constraints
- Each preparation center's capacity must not be exceeded.
- Apple distribution from centers to stores cannot exceed what was received at the center.
- Deliveries to stores must meet or exceed the store's demand for organic apples.

## Decision Variables
- \( x_i \): Quantity of apples transported from the orchard to preparation center _i_ . 
- \( y_ij \): Quantity of apples transported from preparation center _i_ to specialty store _j_ .

## Algebraic Formulation
The mathematical model aims to minimize the total cost _Z_ of transportation and preparation across the entire supply chain, incorporating the costs associated with each segment of the distribution process.

## Implementation
The optimization model has been implemented in a Python Jupyter Notebook (Food_supply_chain.ipynb) and an Excel file (Food_supply_excel.xlsx) with solver capabilities, utilizing both Python programming and AMPL modeling language.

## Results
The model successfully identified the optimal distribution strategy that minimizes the total cost to $3040. The solution specifies the distribution of apples to each preparation center and subsequently to each specialty store, ensuring the demand is met efficiently within the given constraints.

For comprehensive details on the model development, implementation steps, and a detailed solution breakdown, please refer to the provided Jupyter Notebook and Excel files.
