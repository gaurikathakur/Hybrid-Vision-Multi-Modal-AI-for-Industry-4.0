# 🏭 Industry 4.0: Autonomous Industrial Diagnostic Suite

## 🚀 Overview
This project presents a **Hybrid AI Pipeline** designed for smart manufacturing environments. It integrates **Time-Series Forecasting** and **Computer Vision** to create an automated "Predictive Maintenance" system.

## 🛠️ Technical Depth
* **ML Watchman (Predictive):** A **Random Forest Regressor** trained on NASA C-MAPSS data to predict the **Remaining Useful Life (RUL)** of machinery based on sensor telemetry (Temperature, Pressure, Fan Speed).
* **DL Specialist (Diagnostic):** A fine-tuned **MobileNetV2** (Transfer Learning) that classifies 6 types of structural steel defects from the NEU Surface Defect Database.
* **Autonomous Logic:** The system features an automated trigger mechanism—visual diagnostic scans are only initiated when the ML model detects an RUL threshold of < 30 cycles, optimizing computational resources.

## 💻 Tech Stack
* **Language:** Python
* **Libraries:** TensorFlow, Keras, Scikit-Learn, Pandas, NumPy
* **UI/Deployment:** Gradio, Custom CSS, Hugging Face Spaces

## 📊 Results
* **Regression Accuracy:** [Insert your R2 Score here, e.g., 0.82]
* **Classification Accuracy:** [Insert your Val_Accuracy here, e.g., 91%]
