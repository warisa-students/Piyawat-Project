# Topic

## Overview
This project develops a data-driven framework to forecast rainfall and optimize crop planning in non-irrigated agricultural areas.  
The system integrates Machine Learning models with an optimization model to support decision-making under water constraints.

---

## Objectives
- Forecast monthly rainfall using historical weather data  
- Improve planning accuracy under uncertain climate conditions  
- Optimize planting schedules and land allocation  
- Maximize agricultural returns while minimizing drought risk  

---

## Data
Input features include:
- Rainfall  
- Temperature  
- Humidity  
- Wind Speed  
- Atmospheric Pressure  

Target:
- Monthly rainfall prediction  

---

## Machine Learning Models
The following models are used:
- Random Forest (RF)  
- Support Vector Machine (SVM)  
- XGBoost  
- Long Short-Term Memory (LSTM)  
- TimeXer (Transformer-based model)  

---

## Optimization Model
- Mixed-Integer Linear Programming (MILP)  
- Uses predicted rainfall as input  
- Determines:
  - Optimal planting schedule  
  - Land allocation strategy  

---

## Study Area
- Focus on drought-prone, non-irrigated agricultural areas  
- Initial case study: (e.g., Tak Province, Thailand)  

---

## Workflow
1. Collect historical weather data  
2. Preprocess and engineer features  
3. Train ML/DL models for rainfall prediction  
4. Evaluate model performance  
5. Feed predictions into MILP model  
6. Generate optimal crop planning strategy  

---

## Expected Outcomes
- Accurate rainfall forecasts  
- Improved crop planning decisions  
- Reduced risk from drought  
- Increased economic returns for farmers  

---

## Future Work
- Integrate soil moisture and satellite data  
- Expand to multiple regions  
- Develop real-time decision support system  

---

## Tools & Technologies
- Python  
- Scikit-learn  
- XGBoost  
- TensorFlow / PyTorch  
- Optimization (e.g., PuLP / Gurobi / CPLEX)  

---

## Author
Piyawat Sasomsin  
Faculty of Engineering, Chiang Mai University  