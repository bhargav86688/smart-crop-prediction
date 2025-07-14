 🌾 AgriSmart: Smart Crop Prediction

AgriSmart is an AI-powered crop recommendation system that helps farmers and agricultural planners select the most suitable crop based on soil and environmental parameters. Built using machine learning models, the system predicts the best crop for a given input and provides an easy-to-use web interface for users.


📌 Project Highlights

- 🔍 **ML-based prediction** using Random Forest Classifier
- 📊 Input features: Nitrogen (N), Phosphorus (P), Potassium (K), Temperature, Humidity, pH, and Rainfall
- 🌐 **Flask Web App** frontend with real-time crop recommendation
- 📁 Model and Scalers are pre-trained and loaded for fast prediction
- 💡 Designed to assist farmers and agri-tech startups with decision-making

---

 📁 Dataset Used

The dataset contains the following features:

- `N` - Nitrogen level in soil
- `P` - Phosphorus level in soil
- `K` - Potassium level in soil
- `temperature` - Environmental temperature (°C)
- `humidity` - Humidity percentage
- `ph` - Soil pH value
- `rainfall` - Rainfall in mm
- `label` - Recommended crop

> Dataset Source: Open-source crop recommendation dataset from Kaggle or similar repositories.


 🧠 Model Used

- **Random Forest Classifier**
- Achieved high accuracy in crop prediction
- Scaled input using:
  - `StandardScaler` for N, temperature, pH, rainfall
  - `MinMaxScaler` for P
  - `RobustScaler` for K, humidity

Model files used:
- `rf_model_clean.pkl`
- `scaler_standard.pkl`, `scaler_minmax.pkl`, `scaler_robust.pkl`

---

 💻 How to Run Locally

1. **Clone the repository:**
```bash
git clone https://github.com/bhargav86688/smart-crop-prediction.git
cd smart-crop-prediction
