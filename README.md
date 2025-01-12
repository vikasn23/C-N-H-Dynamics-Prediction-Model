# C-N-H Prediction Model Using LSTM

# **Objective**
The objective of this project is to develop a predictive model using Long Short-Term Memory (LSTM) neural networks to simulate and forecast the concentrations of chlorine (C), organic matter (N), and trihalomethanes (H) under varying initial conditions and temperature scenarios. The model aims to enhance the understanding of chemical dynamics in water treatment systems and improve decision-making for process optimization and compliance with environmental standards.

# **Dataset Introduction**
This dataset was generated using simulated chemical reaction data. It represents the behavior of chlorine (C), organic matter (N), and trihalomethanes (H) in water treatment systems under different conditions.
## Features and Parameters:
* C_initial: Initial concentration of chlorine.
* N_initial: Initial concentration of organic matter.
* Y_n: Yield coefficient for organic matter consumption.
* Y_h: Yield coefficient for trihalomethane formation.
* Temperature: Temperature of the reaction system (°C).
* Time: Time elapsed during the reaction (s).
* C: Concentration of chlorine over time.
* N: Concentration of organic matter over time.
* H: Concentration of trihalomethanes over time.
## Data Size:
* Number of simulations: 100
* Time steps per simulation: 720
* Total rows: 72,000

# **Model Highlights**
* Model Type: Deep learning model using LSTM architecture for time-series prediction.
* Inputs: Temperature, time, and initial conditions (C_initial, N_initial, Y_n, Y_h).
* Outputs: Predicted concentrations of C, N, and H over time.

# **Conclusion**
* The model effectively predicts the concentrations of chlorine, organic matter, and trihalomethanes for a wide range of initial conditions and temperatures, enabling better process monitoring and optimization.
* While the model performs well for standard water treatment scenarios, it shows reduced accuracy for extreme temperature conditions or scenarios with very high or low initial chemical concentrations.
* Future work could focus on retraining the model on specific subsets of data (e.g., extreme conditions) or integrating additional features (e.g., pH levels or reaction inhibitors) to improve predictions across all scenarios.





 

