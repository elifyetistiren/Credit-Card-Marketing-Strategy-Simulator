
# 💳 Credit Card Marketing Campaign Simulator

This project simulates and evaluates a targeted marketing campaign for acquiring new customers for a credit card or loan product. It includes customer segmentation, A/B testing, and ROI analysis.

---

## 📌 Objective

To identify high-value customer segments, simulate a marketing campaign with A/B testing, and evaluate its effectiveness based on conversion and revenue metrics.

---

## 🧰 Tools & Technologies

- Python (Pandas, NumPy, scikit-learn, Matplotlib)
- Power BI
- Excel
- UCI Bank Marketing Dataset via `ucimlrepo`

---

## 🧪 Key Steps

### 1. Data Preparation
- Loaded UCI Bank Marketing data
- Selected features: age, balance, duration, campaign, etc.

### 2. Customer Segmentation
- Applied **KMeans Clustering** to create customer segments based on demographics and behavior
- Identified high-converting groups like **High-Spend Professionals** and **Moderate-Income Workers**

### 3. A/B Test Simulation
- Simulated Group A (control) and Group B (treatment)
- Group B received the marketing campaign
- Assigned conversion probabilities: 2% (A), 5% (B)
- Simulated post-conversion spend using normal distribution

### 4. Campaign Evaluation
- Measured conversion lift, revenue lift, and ROI
- Key Metrics:
  - 📈 **Conversion Lift**: +2.85%
  - 💰 **Revenue Lift**: $149,403
  - 💡 **ROI**: 9.56x

---

## 📊 Dashboard Output

![Campaign Performance Dashboard](./Campaign_Performance.png)

---

## 📁 Files Included

- `Credit_Card_Campaign_Simulation.ipynb`: Jupyter Notebook for code and analysis
- `Credit_Card_Campaign_Results.xlsx`: Excel with raw data, summary, ROI
- `Campaign_Performance.png`: Power BI dashboard visualization
- `README.md`: Project summary

---

## 🚀 Why It Matters

This project mirrors real-world product and marketing strategy scenarios at companies like **Capital One**, demonstrating:
- Data-driven decision-making
- Campaign effectiveness evaluation
- Customer segmentation strategy

---

## 📬 Contact

For questions or collaboration, reach out via [LinkedIn](https://linkedin.com).

