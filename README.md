# 🏥 Patient Vital Signs Prediction using GRU

# 🚀 Project Overview

- This project predicts patient vital signs, specifically heart rate, using a GRU (Gated Recurrent Unit) neural network. GRUs are ideal for time-series prediction, making them perfect for healthcare data like patient vitals.

- By learning from historical patterns, the model can forecast heart rate trends, which can assist in early detection of abnormalities and healthcare monitoring.

# 🛠️ Technologies & Libraries

- Python 🐍 – Programming language

- TensorFlow / Keras 🤖 – For building GRU model

- NumPy & Pandas 📊 – Data manipulation

- Matplotlib 📈 – Visualizations

- scikit-learn 🔧 – Data preprocessing (MinMaxScaler)

# 📝 Key Steps in the Project

# 1️⃣ Load or Generate Data

- Simulated healthcare dataset including Heart Rate and Blood Pressure.

- Dataset has 2000 time steps for training the model.

# 2️⃣ Preprocessing

- Normalize data using MinMaxScaler.

- Create sequences of 20 time steps for GRU input.

- Split dataset into training (80%) and testing (20%).

# 3️⃣ Build GRU Model

- Two GRU layers with 128 and 64 units.

- Dropout layers (0.3) to prevent overfitting.

- Dense layer predicts Heart Rate.

# 4️⃣ Train Model

- Compile with Adam optimizer and MSE loss.

- Use EarlyStopping to prevent overfitting.

- Validation split of 10% during training.

# 5️⃣ Prediction & Evaluation

- Predict heart rate for test data.

- Inverse transform normalized values to original scale.

- Compare predicted vs actual heart rates.

# 6️⃣ Visualization

- Plot actual vs predicted heart rates using Matplotlib.

# 📊 Results

- The model predicts heart rate trends accurately and can help visualize patient vitals over time, which can support healthcare monitoring and analysis.

# 💡 Features

- Predict patient Heart Rate using time-series data.

- Realistic simulated dataset for healthcare applications.

- GRU-based model with dropout for robustness.

- Visual comparison of actual vs predicted heart rates.

# ⚡ Future Improvements

- Include additional vitals like blood pressure, oxygen levels, respiration rate.

- Predict multiple vitals simultaneously using multi-output GRU.

- Use LSTM or hybrid GRU-LSTM models for improved performance.

- Integrate real hospital datasets for clinical accuracy.
