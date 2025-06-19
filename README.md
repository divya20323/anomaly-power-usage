
# 🔌 Anomaly Detection in Power Usage

This project uses **real-world household power consumption data** to detect anomalies using two powerful techniques:

- ✅ Isolation Forest (unsupervised machine learning)
- ✅ Autoencoder (deep learning)

---

## 📊 Dataset

- Source: [UCI Household Power Consumption Dataset](https://archive.ics.uci.edu/ml/datasets/individual+household+electric+power+consumption)
- Data: 2+ million readings of household power usage from 2006 to 2010
- Used `Global_active_power` resampled to **hourly averages**

---

## 📈 Techniques Used

| Model             | Description                                 |
|------------------|---------------------------------------------|
| **Isolation Forest** | Detects outliers using tree-based partitioning |
| **Autoencoder**       | Learns to reconstruct normal patterns, flags deviations |

---

## 🔍 Comparison Summary

- Isolation Forest: Fast, good at sharp anomalies
- Autoencoder: Better at subtle + sharp anomalies, uses reconstruction error
- Both models visualized and compared

---

## 🧪 Results

### 🔴 Isolation Forest Output
![IF sample](docs/if_plot.png)

### 🟣 Autoencoder Output
![AE sample](docs/ae_plot.png)

---

## 📁 Project Structure
anomaly-power-usage/
├── python.ipynb # Final notebook with code, plots, and outputs
├── README.md # This project overview file
