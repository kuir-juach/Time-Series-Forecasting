**Beijing Air Quality Forecasting**
**Project Overview**

This project is part of the Machine Learning Techniques I course and focuses on forecasting PM2.5 air pollution levels in Beijing using Recurrent Neural Networks (RNNs) and Long Short-Term Memory (LSTM) models.

Accurately forecasting PM2.5 concentrations is crucial for supporting environmental policies, protecting public health, and enabling timely interventions.

**Objectives**


1. Preprocess sequential air quality and meteorological datasets.

2. Design and train RNN/LSTM models tailored for time-series forecasting.

3. Fine-tune model architectures and hyperparameters for optimal performance.

4. Evaluate model accuracy using standard metrics.

5. Generate final predictions of PM2.5 levels.

**Best Performing Model**

-After multiple experiments with different architectures, the following model demonstrated the best performance in minimizing RMSE and maintaining generalization.

**LSTM Architecture**

1. First LSTM layer with 128 units

2. Activation: ReLU

3. Regularization: L2

4. Dropout layer (20%)

5. Second LSTM layer with 64 units

6. Activation: ReLU

Regularization: L2

Dropout layer (20%)

Dense Layers
Dense layer with 32 units

Activation: ReLU

Regularization: L2

Output layer with 1 unit for PM2.5 prediction

**Training Configuration**
Optimizer: Adam (learning rate = 0.001)

Loss Function: Mean Squared Error (MSE)

Evaluation Metric: Root Mean Squared Error (RMSE)

Final Performance (RMSE): 70.45

Training Epochs: 10

Batch Size: 32

**Repository Structure**

├── data/              
├── notebook/          
├── models_output/    
├── README.md        

**Setup Instruction**
1. To run the project locally:
Clone Repository: https://github.com/kuir-juach/Time-Series-Forecasting.git
2. Run the Jupyter Notebook. 
Navigate to the notebook directory and open the model training notebook
**Contributor**
Kuir Juach Kuir Thuch



