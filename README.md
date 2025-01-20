# Project 1: Battery State Estimation Using Asymmetric-Transformer
### 📅 Project Duration
September 2023 - September 2024
### 🎯 Objective
Enhance SOC estimation accuracy with an Asymmetric-Transformer model that leverages current derivative data.
### 🛠 Tech Stack
Language: Python 3.10.9
Library: PyTorch 2.0.0+cu118
### 📂 Project Location
Files are located in the 'Project1_Using Asymmetric-Transformer' folder of this repository.
### 📜 Project Description
This project aimed to improve SOC estimation accuracy by developing an Asymmetric-Transformer model. By focusing on the rate of change in current data, the model reduced parameters by 32% while achieving higher accuracy. Compared to traditional LSTM and standard Transformer models, this approach provided substantial performance gains.
![image](https://github.com/user-attachments/assets/3db3c25d-28ba-443c-92e8-86bfbe5568d4)
### 📈 Results
Performance Improvement: Achieved 52% improvement over LSTM and 48% over standard Transformer in accuracy.

-----------------

# Project 2: Battery State Estimation Using CNN-Transformer
### 📅 Project Duration
January 2024 - January 2025
### 🎯 Objective
Combine CNN and Transformer strengths to improve SOC estimation accuracy by capturing both global and local data features.
### 🛠 Tech Stack
Language: Python 3.10.9
Library: PyTorch 2.0.0+cu118
### 📂 Project Location
Files are located in the 'Project2_Using CNN-Transformer' folder of this repository.
### 📜 Project Description
This project leverages CNN and Transformer layers to simultaneously address global and local patterns in SOC estimation. The CNN layers enhance positional information in the input data, effectively overcoming Transformer limitations. Experimentally, this model achieved a 44% reduction in loss compared to the LSTM model.
![image](https://github.com/user-attachments/assets/7a81e5f7-9d9e-469e-9f19-2ef597d7f5cc)

### 📈 Results
Loss Reduction: 44% lower loss than the LSTM model, indicating improved SOC prediction accuracy.
