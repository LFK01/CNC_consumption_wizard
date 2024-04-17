## CNC Energy Consumption

### Aim of the study
As stakeholders, we request a comprehensive analysis of the dataset to explore energy usage patterns and their correlations with CNC machine performance and productivity. Considering that each CNC machine occupies a distinct room of identical dimensions, with each room having the same number of walls in contact with the outside, our objective is to uncover insights that will help us identify opportunities for developing predictive energy consumption models based on environment sensors.\
Objectives
- **Main:** We aim to evaluate the feasibility of developing a predictive model tailored to estimate the 10-minute average energy consumption of the factory by utilizing data obtained from sensors within the preceding 1 to 4 hours. By employing data collected from sensors, we seek to determine the most effective time window and approach for making these estimates. It is recommended to present the results and the chosen methodology in a Python notebook.
- **Bonus 1:** Create a web application that enables users to employ the trained model for predicting new instances. Display the comparison between actual and predicted factory usage in a time series plot. If feasible, develop the web application using the Streamlit framework and generate the plot using the Plotly graphing library.
- **Bonus 2:** Deploy the application using Docker.