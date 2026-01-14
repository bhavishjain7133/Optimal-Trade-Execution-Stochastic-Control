# Optimal Trade Execution under Market Impact using Stochastic Control

This project implements the Almgren–Chriss model to study optimal liquidation
of large orders under market impact.

The problem is formulated as a stochastic control and operations research
optimization task, and the optimal trading schedule is compared with naive
time-uniform execution.

## Features
- Market impact price simulator
- Optimal execution schedule using closed-form Almgren–Chriss solution
- Execution cost and inventory risk comparison
- Visualization of inventory depletion and price evolution

## Tech Stack
Python, NumPy, Matplotlib, Jupyter Notebook (Deepnote)

## Results
The optimal execution strategy significantly reduces both execution cost and
inventory risk relative to naive execution.
