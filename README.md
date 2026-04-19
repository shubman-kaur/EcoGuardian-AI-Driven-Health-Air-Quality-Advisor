# 🌍 EcoGuardian: AI-Driven Health & Air Quality Advisor

**EcoGuardian** is an intelligent system that decodes complex industrial pollutant data into life-saving medical actions. By utilizing a Random Forest architecture, we bridge the gap between raw air quality sensors and proactive respiratory safety.

## 🚀 Key Features
- **Predictive AQI Modeling:** Real-time prediction of AQI based on $SO_2$, $NO_2$, and Particulate Matter ($RSPM/SPM$).
- **Health Intelligence:** Translates numerical pollution data into actionable healthcare advice.
- **Data-Driven Insights:** Identifies the most significant pollutants affecting a specific region.
- **Lightweight Architecture:** Designed for edge deployment in smart city dashboards or IoT sensors.

## 🛠️ Technical Stack
- **Language:** Python 3.x
- **Libraries:** Scikit-Learn (Machine Learning), Pandas (Data Manipulation), NumPy (Numerical Analysis), Matplotlib/Seaborn (Visualization).
- **Environment:** Google Colab / Jupyter Notebook.

## 📊 How It Works
The model follows a rigorous 4-step pipeline:
1. **Cleaning:** Standardizing raw sensor logs and handling missing values ($NA$).
2. **Engineering:** Calculating a custom AQI index from localized Indian pollutant data.
3. **Training:** Implementing a **Random Forest Regressor** to capture non-linear environmental patterns.
4. **Inference:** Generating a health report with specific precautions for sensitive groups.

## 🏁 Getting Started
### Prerequisites
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
