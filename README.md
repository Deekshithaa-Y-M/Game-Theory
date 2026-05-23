# 🚑 CityGuard: Intelligent Emergency Medical Service Network Optimizer

> A research-grade Operations Research + Machine Learning system for optimizing ambulance deployment, emergency response routing, and EMS system performance using real-world city-scale data.

---

## 📌 Overview

CityGuard is a full-stack urban emergency response optimization platform that combines:

- 📈 Machine Learning demand forecasting
- 📍 Facility location optimization
- 🚑 Vehicle routing algorithms
- ⏳ Queueing theory
- 🎲 Stochastic simulation
- 🧮 Integer programming

to model and optimize emergency medical service (EMS) systems using publicly available city-scale data and real road networks.

The system predicts emergency demand hotspots, determines optimal ambulance station placement, dispatches ambulances efficiently under traffic constraints, and evaluates system performance through simulation.

---

# 🌍 Why This Project Matters

Emergency response time directly impacts survival rates in:
- cardiac arrest,
- trauma,
- stroke,
- respiratory emergencies.

Even a small reduction in ambulance response time can significantly improve patient outcomes.

Unlike toy ML projects, CityGuard solves a real public-systems optimization problem with measurable operational impact.

---

# 🎯 Core Research Objective

Minimize EMS response times while maximizing emergency coverage under limited ambulance and infrastructure constraints.

---

# 🧠 System Pipeline

```text
Historical EMS Data
        ↓
ML Demand Forecasting
        ↓
Spatial Demand Heatmaps
        ↓
Facility Location Optimization
        ↓
Ambulance Allocation (ILP)
        ↓
Vehicle Routing + Dispatch
        ↓
Queueing + System Simulation
        ↓
Performance Evaluation
