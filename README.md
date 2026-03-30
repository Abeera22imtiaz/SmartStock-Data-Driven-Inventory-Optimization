# SmartStock: Data-Driven Inventory Optimization 📊

SmartStock is a statistical engine designed to solve the retail dilemma of stock-outs and overstocking. By analyzing **900,000+ sales records**, it replaces "simple average" stocking with **Precision Reorder Points** based on store-specific volatility.

---

## 🎯 Project Goals

- **Identify Patterns:**  
  Validated a **20% surge in weekend demand** using 2-Sample T-Testing *(p < 0.05)*  

- **Quantify Risk:**  
  Profiled each store using the **Coefficient of Variation (CV)** to detect high-volatility locations  

- **Automate Levels:**  
  Calculated **Safety Stock** and **Reorder Points** using a **95% Service Level model**  

---

## 🛠️ Tech Stack

- **Analysis:** Python *(Pandas, SciPy, Seaborn)*  
- **Statistics:** Z-Score Outlier Removal, T-Tests, Normality Distribution *(Q-Q Plots)*  
- **Visualization:** [View Interactive Tableau Dashboard](https://public.tableau.com/views/smartstock/Story1)

---

## 📈 Key Results

- **Inventory Precision:**  
  Customized stock levels for **10 unique store profiles**  
  *(e.g., Store 2: 114 units vs Store 7: 67 units)*  

- **Efficiency:**  
  Optimized **Friday replenishment cycles** to capture weekend growth while minimizing wasted capital  

---

## 🚀 Future Improvements

- Integrate real-time data for dynamic inventory updates  
- Apply machine learning models for demand forecasting  
- Deploy as a web-based dashboard for business use  
