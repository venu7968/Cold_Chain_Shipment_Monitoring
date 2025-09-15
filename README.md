# Cold_Chain_Shipment_Monitoring
## 📌 Project Overview  
This project ensures safe transportation of vaccines and other temperature-sensitive medical supplies.  
It monitors multiple sensors in real-time (temperature, humidity, shock, GPS, battery health) and detects violations that may put the shipment at risk.  
## 🛠 Features  
- **Data Model:** ER schema for shipments, sensors, readings, and violations.  
- **Rules & Violations:** Detects threshold breaches, spikes, sustained violations, missing data, and correlated events.  
- **Sample Dataset:** 5 shipments × 10+ readings per sensor (synthetic data with intentional violations).  
- **Reports:** Generates per-shipment summary (avg/min/max, violation counts, overall risk score).  
- **Risk Assessment:** Weighted risk scoring with Low / Medium / High categories.  
- **Visualizations:** Time-series plots marking violations.
## 🚀 How It Works  
1. Load sensor readings into the data model.  
2. Apply rules to detect threshold violations and anomalies.  
3. Generate shipment summary report in **JSON and CSV format**.  
4. Plot sensor time-series graphs with highlighted violations.
