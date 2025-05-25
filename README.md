
# 🌍 Marmara Fault-Earthquake Interactions (2000–2025)

Welcome to **Marmara Fault-Earthquake Interactions (2000–2025)**! This repository contains earthquake event data, fault dynamics, and interaction patterns for the Marmara Fault region over the last 25 years. The dataset is useful for seismic research, trend analysis, and hazard assessment.

## 📌 Dataset Overview
- 🌐 **Region Covered:** Marmara Fault Zone (Turkey)  
- 📅 **Time Period:** Earthquake records from **2000–2025**  
- 📊 **Data Parameters:** Magnitude, depth, epicenter coordinates, fault slip rates, and interactions  
- 🔍 **Analysis:** Seismic patterns, aftershock distribution, and stress accumulation  

## 📂 Data Format
The dataset is structured in CSV format with the following key columns:
- `Date` – Earthquake occurrence date (YYYY-MM-DD)  
- `Time (UTC)` – Time of event in coordinated universal time  
- `Latitude` – Epicenter latitude  
- `Longitude` – Epicenter longitude  
- `Magnitude (Mw)` – Earthquake magnitude on the Moment Magnitude Scale  
- `Depth (km)` – Depth of the earthquake focus  
- `Fault Segment` – Affected fault section  

## 🔧 How to Use
Clone the repository and start exploring the data:
```bash
git clone https://github.com/yourusername/Marmara-Fault-Earthquake-Interactions.git
cd Marmara-Fault-Earthquake-Interactions


Load the dataset using Python:
import pandas as pd
data = pd.read_csv("Marmara_Earthquake_2000_2025.csv")
print(data.head())


📊 Applications
- Seismic Risk Analysis: Understanding earthquake frequency and intensity
- Hazard Preparedness: Evaluating potential high-risk zones for future events
- Tectonic Insights: Assessing fault slip rates and earthquake stress interactions
🤝 Contributions
Contributions are welcome! If you have additional datasets or improved analysis models, feel free to submit a pull request or suggest changes.
📜 License
This project is licensed under the MIT License. See the LICENSE file for details
