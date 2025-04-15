# 🧮 Customer Segmentation using RFM Analysis

This project applies **Recency, Frequency, and Monetary (RFM) analysis** to segment customers based on their purchase behavior. It enables businesses to identify customer segments such as loyal customers, at-risk customers, and potential churners, helping in targeted marketing strategies.

## 📊 Overview

The project demonstrates how to:
- Perform **data preprocessing and cleaning** on transactional data.
- Calculate RFM metrics for each customer.
- Apply **K-Means clustering** to segment customers based on their RFM scores.
- Visualize customer segments using **bar plots**, **box plots**, and **elbow method** for optimal cluster selection.
- Provide actionable insights for marketing and customer engagement.

## 📁 Project Structure

```
Customer-Segmentation-RFM-Analysis/
│
├── data/
│   └── online_retail.csv            # Raw dataset (from UCI ML Repository)
│
├── notebooks/
│   └── customer_segmentation.ipynb  # Main analysis notebook
│
├── outputs/
│   └── plots/                       # Visualizations and cluster insights
│
└── README.md                        # Project documentation (you are here)
```

## 🛠️ Tech Stack

- **Python 3.8+**
- **Pandas** – data manipulation
- **Matplotlib / Seaborn** – data visualization
- **Scikit-learn** – clustering and scaling
- **Jupyter Notebook**

## 📈 RFM Model

| Metric     | Description                                                 |
|------------|-------------------------------------------------------------|
| **Recency** | Days since the last purchase                               |
| **Frequency** | Total number of purchases                                |
| **Monetary** | Total amount spent by the customer                        |

Each customer is scored based on these metrics, scaled using MinMaxScaler, and clustered using K-Means.

## 🧪 Clustering & Insights

- **Elbow method** is used to determine optimal number of clusters (found to be 4).
- Customer segments are labeled and analyzed:
  - 🎯 **Loyal Customers**
  - ⚠️ **At-Risk Customers**
  - 🆕 **New Customers**
  - 💸 **Big Spenders**

These clusters can inform targeted marketing campaigns and personalized experiences.

## 📊 Sample Visualizations

- Bar plots of mean RFM values by cluster
- Box plots for Recency, Frequency, and Monetary across segments
- Elbow method plot for optimal `k` selection

## 🧠 Business Implications

- **Retention strategies** for high-value but low-recency customers
- **Loyalty programs** for frequent buyers
- **Promotional targeting** for less engaged customer segments

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Customer-Segmentation-RFM-Analysis.git
   cd Customer-Segmentation-RFM-Analysis
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook:
   ```bash
   jupyter notebook notebooks/customer_segmentation.ipynb
   ```

## 🙌 Acknowledgements

Inspired by customer analytics techniques in retail and e-commerce. Visualization styles influenced by common data science best practices.

## 📬 Contact

For any queries or collaborations, reach out to:  
**TARIQUE ANWAR** – [LinkedIn](https://www.linkedin.com/in/tarique-anwar-bb8535a1/) | tarique.dts@gmail.com

---

```

Let me know if you'd like a matching `requirements.txt`, visuals for uploading, or help customizing the README for deployment or a portfolio!
