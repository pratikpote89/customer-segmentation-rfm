# Customer Segmentation Using RFM Analysis & K-Means Clustering

## 📌 Business Problem
Marketing teams need to understand their customer base to deliver targeted campaigns. This project segments customers based on their purchasing behavior to enable personalized marketing strategies.

## 🎯 Objectives
- Segment customers using RFM (Recency, Frequency, Monetary) analysis
- Apply K-means clustering to identify distinct customer groups
- Provide actionable recommendations for each segment

## 📊 Dataset
- **Source:** [UCI Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail+II)
- **Records:** ~500K transactions
- **Time Period:** Dec 2010 - Dec 2011
- **Features:** InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

## 🛠️ Methodology
1. **Data Cleaning:** Handle missing values, remove duplicates, filter invalid transactions
2. **RFM Calculation:** Compute Recency, Frequency, and Monetary value per customer
3. **Feature Engineering:** Scale features, handle outliers
4. **Clustering:** Apply K-means with elbow method for optimal K
5. **Segment Profiling:** Analyze and name each customer segment
6. **Recommendations:** Marketing strategies per segment

## 📈 Key Findings
*[To be updated after analysis]*

| Segment | Size | Characteristics | Recommended Action |
|---------|------|-----------------|-------------------|
| Champions | X% | High value, recent, frequent | Loyalty rewards |
| At Risk | X% | Were good, haven't bought recently | Win-back campaign |
| ... | ... | ... | ... |

## 🔧 Tech Stack
- **Python:** pandas, numpy, scikit-learn, matplotlib, seaborn
- **Clustering:** K-means
- **Visualization:** Plotly (interactive), Seaborn (static)

## 📁 Project Structure
```
├── data/                    # Raw and processed data
├── notebooks/               # Jupyter notebooks
├── src/                     # Python modules
├── visualizations/          # Charts and graphs
├── reports/                 # Analysis reports
└── README.md
```

## 🚀 How to Run
```bash
# Clone repository
git clone https://github.com/pratikpote89/customer-segmentation-rfm.git
cd customer-segmentation-rfm

# Install dependencies
pip install -r requirements.txt

# Run analysis
jupyter notebook notebooks/01_data_exploration.ipynb
```

## 📧 Contact
**Pratik Pote**  
- LinkedIn: [linkedin.com/in/pratikpote](https://linkedin.com/in/pratikpote)
- Email: pratik.pote89@gmail.com

---
*This project is part of my Marketing Analytics Portfolio demonstrating customer analytics capabilities.*