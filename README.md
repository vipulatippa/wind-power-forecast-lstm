## wind-power-forecast-lstm
This project implements a deep learning-based approach to forecast wind turbine power output using **LSTM (Long Short-Term Memory)** neural networks. The model uses historical SCADA data to perform **multi-step ahead forecasting**.

## 📌 Project Highlights

- Data Source: Wind Turbine SCADA Dataset from Kaggle  
- Forecast Horizon: 3-step ahead power forecasting  
- Model: LSTM with ReLU activation  
- Frameworks: TensorFlow/Keras, Scikit-learn  
- Visualization of actual vs predicted wind power output

---

## 📂 Dataset

The dataset is publicly available and sourced from Kaggle:  
🔗 [Wind Turbine SCADA Dataset on Kaggle](https://www.kaggle.com/datasets/berkerisen/wind-turbine-scada-dataset)

📈 Results Preview
Here’s a sample of the forecasting performance for +1 and +3 time steps:


🚀 Future Improvements
1. Expand to full wind farm-level forecasting

2. Integrate with live SCADA feeds

3. Use ensemble or hybrid models

4. Build a Streamlit dashboard for internal review

🤝 Acknowledgements
Dataset by Berker Isen on Kaggle

TensorFlow, Keras, Matplotlib, Scikit-learn for the ML stack

---

## 🔧 Installation & Setup

```bash
# Clone the repository
git clone https://github.com/yourusername/wind-power-forecast-lstm.git
cd wind-power-forecast-lstm

# Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

