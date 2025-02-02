# AI-Based Energy Optimization for Telecom Sites

## 📌 Project Overview
This project leverages **Machine Learning (ML) and IoT sensor data** to optimize energy consumption in telecom sites. The system predicts **energy efficiency**, recommends **optimization strategies**, and provides insights into **battery health and power consumption** trends.

## 🚀 Features
- 📊 **Predictive Maintenance**: Forecasts battery health to reduce unexpected failures.
- 🔍 **Energy Consumption Analysis**: Identifies inefficiencies and suggests optimizations.
- 📉 **Feature Importance Analysis**: Determines which factors affect energy efficiency most.
- 📡 **IoT Data Integration**: Uses real-time sensor data for energy monitoring.
- 📈 **Tableau Dashboard**: Interactive visualizations for insightful decision-making.

## 🛠️ Tech Stack
- **Python**: Data processing & ML model training
- **Scikit-Learn**: Machine learning (Random Forest)
- **Pandas & NumPy**: Data handling
- **Matplotlib & Seaborn**: Data visualization
- **SQL**: Data storage & retrieval
- **Tableau**: Dashboard for data visualization

## 📂 Dataset
The dataset contains **IoT sensor readings** collected from telecom sites, including:
- Temperature (°C)
- Voltage (V)
- Power Consumption (W)
- Battery Health (0-1 scale)
- Energy Efficiency Score (0-100 scale)

🔗 **[Download Dataset](sandbox:/mnt/data/iot_energy_data.csv)**

## 🏗️ How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/AI-Energy-Optimization.git
   cd AI-Energy-Optimization
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
3. Run the **Python model**:
   ```bash
   python energy_optimization.py
   ```
4. Load the dataset into **Tableau** and create the dashboard.

## 📊 Tableau Dashboard
Follow the steps to create an **interactive energy optimization dashboard** in Tableau:
1. Load `iot_energy_data.csv` into Tableau.
2. Create visualizations for energy trends, feature importance, and efficiency predictions.
3. Arrange visualizations into a **dashboard** for interactive insights.
4. Publish and share the dashboard.

## 📜 Future Enhancements
- 🏭 **Real-time energy monitoring** with live IoT data streaming.
- 🤖 **Deep learning models** for more accurate predictions.
- 📡 **API integration** for remote energy monitoring.

## 🤝 Contributing
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit changes (`git commit -m "Added new feature"`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.

## 📄 License
This project is **open-source** and available under the **MIT License**.
