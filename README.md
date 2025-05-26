# 🦟 Analysis of Malaria Cases in Florida

This project investigates the transmission dynamics of malaria in Florida using a spline-based SEIR (Susceptible–Exposed–Infectious–Recovered) model with seasonal and immigration covariates.

## 🔍 Overview
We built a stochastic compartmental model in **R** using the `pomp` package to:
- Simulate malaria spread under varying climate and migration conditions
- Estimate key epidemiological parameters
- Evaluate model performance using particle filtering and likelihood profiles

## 📈 Key Features
- **Spline-based transmission modeling**: Captures seasonality in malaria spread  
- **Iterated filtering (mif2)** for parameter optimization  
- **Profile likelihood** and **simulation-based confidence intervals** to assess uncertainty  
- **Parallel computation** with `foreach` and `doFuture` for scalable inference  
- Visualization of simulated trajectories against real data for model validation

## 📁 Output
The HTML report includes:
- Model specifications and assumptions  
- Parameter estimation process  
- Simulations of outbreak trajectories  
- Comparative model diagnostics

## ⚙️ Technologies Used
- `R`, `pomp`, `ggplot2`, `foreach`, `doFuture`  
- SEIR modeling, Bayesian inference, stochastic simulation

---

## 💡 Motivation
This analysis was part of a graduate-level data science course project at the University of Michigan, aimed at understanding how **seasonal factors** and **external immigration** affect vector-borne disease dynamics in a non-endemic region.
