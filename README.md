# 🌊 FloodWatch AI  
### A Location-Based Community Flood Risk Prediction & Resilience System  

FloodWatch AI is an AI-powered, location-based flood risk prediction and community alert platform designed to enhance localized disaster preparedness and climate resilience.

---

## 🚩 Problem Statement

Flooding remains one of the most destructive natural disasters in India. Traditional flood warning systems often:

- Depend primarily on rainfall thresholds  
- Lack infrastructure-level risk indicators  
- Provide delayed alerts  
- Do not integrate citizen-level reporting  

There is a need for a scalable, intelligent, and community-integrated flood risk assessment system.

---

## 💡 Solution Overview

FloodWatch AI is built as a **community disaster resilience ecosystem**, combining:

1. 🤖 AI-based flood probability prediction  
2. 📍 Location-driven automatic variable derivation  
3. 🗺 Interactive flood risk map  
4. 🚨 Community alert reporting system  

Users only enter their **location**.  
All environmental and infrastructural variables are derived automatically.

---

## 🏗 System Architecture

User
↓
Location Input
↓
Location-Based Variable Extraction
↓
AI Flood Prediction Model (Random Forest)
↓
Flood Probability Output
↓
├── Interactive Map Visualization
└── Community Alert System

---

## 🧠 AI Model Details

- **Model Type:** Random Forest  
- **Training Environment:** Google Colab  
- **Task:** Flood probability prediction  

### Key Features Used:
- Monsoon Intensity  
- Topography Drainage  
- Urbanization  
- Dams Quality  
- Infrastructure Deterioration  
- Watersheds  
- Climate Change Impact  
- Disaster Preparedness  
- Drainage Systems  
- Coastal Vulnerability  
- And additional socio-environmental indicators  

---

## 📊 Model Performance

| Metric        | Value |
|--------------|--------|
| Accuracy     | 78.76% |
| F1 Score     | 79.58% |
| ROC-AUC      | 0.877  |
| R² Score     | 0.578  |

The ROC-AUC of **0.877** demonstrates strong discrimination capability between flood-prone and low-risk regions.

---

## 🌍 Live Deployment

🔗 **Live Platform:**  
https://flood-watch.base44.app/

The web interface allows users to:

- Enter location for AI-based flood probability estimation  
- View geospatial flood risk through an interactive map  
- Submit community alerts such as:
  - Drain blockages  
  - Waterlogging  
  - Infrastructure damage  
  - Rising water levels  

---

## ⚙️ Technologies Used

- Python  
- Scikit-learn  
- Pandas  
- NumPy  
- Matplotlib  
- Google Colab  
- Base44 (Frontend Deployment)  
- GitHub (Version Control)
- ChatGPT (Documentation)  

---

## 🚀 Future Improvements

- Integration of ERA5 climate reanalysis data  
- Integration of GloFAS river discharge forecasts  
- Real-time rainfall ingestion  
- Mobile application deployment  
- Municipal and Smart City system integration  

---

## ⚠️ Limitations

- Model trained on structured dataset representation  
- Real-time hydrological integration pending  
- Community alert effectiveness depends on active user participation  

---

## 📜 License

This project is developed for educational and research purposes.

---

## 👤 Author

Dyutikar G V  
