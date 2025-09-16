# Mall Customer Data Analysis

## 📊 Project Overview

This project performs exploratory data analysis and insights extraction on a mall customer dataset. We aim to understand customer behaviors, segmentation, and key features that influence patterns in spending and demographics.

---

## 📁 Directory Structure

```
Analysis_on_Mall_Coustomer_Data/
├── Mall_Customer_Data.csv          # Dataset with customer info
├── notebooks/                      # Contains analysis notebooks
│   ├── EDA_Mall_Customers.ipynb    # Exploratory data analysis
│   └── Segmentation_Clustering.ipynb # Clustering and segmentation
└── README.md                       # This file
```

---

## 🧮 Data Description

- The dataset typically includes fields such as:  
  `CustomerID`, `Gender`, `Age`, `Annual Income (k$)`, `Spending Score (1-100)`, etc.

- Each row corresponds to a customer of the mall, with demographic and spending behaviour features.

---

## 🔍 Analysis Goals

1. **Exploratory Data Analysis (EDA)**  
   - Summary statistics (mean, median, min, max)  
   - Distribution of numerical features  
   - Frequency counts of categorical variables  
   - Missing values handling  

2. **Visualization**  
   - Histograms, boxplots for numerical attributes  
   - Bar charts for categorical attributes  
   - Pairwise plots / correlations  

3. **Segmentation / Clustering**  
   - Use clustering algorithms (e.g. K‑Means) to segment customers based on income, spending, age, etc.  
   - Try different values of clusters and assess cluster quality (silhouette score, elbow method)

4. **Insights and Recommendations**  
   - Identify which customer segments are high spenders  
   - Understand which demographics correlate with high spending  
   - Offer suggestions for targeted marketing or improvements for the mall

---

## ⚙️ Requirements

- Python 3.x  
- Key libraries:  
  ```
  numpy
  pandas
  matplotlib
  seaborn
  scikit‑learn
  ```
- Jupyter Notebook or JupyterLab to run the `.ipynb` files

Install necessary packages via:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

---

## 🚀 How to Run

1. Clone the repo:

   ```bash
   git clone https://github.com/vritik907/Data-Analysis.git
   ```

2. Navigate to the Mall Customer Analysis folder:

   ```bash
   cd Data-Analysis/Analysis_on_Mall_Coustomer_Data
   ```

3. Ensure the dataset file `Mall_Customer_Data.csv` is present.

4. Open and run the notebooks:

   ```bash
   jupyter notebook
   ```

   - Run `EDA_Mall_Customers.ipynb` for initial exploration.  
   - Run `Segmentation_Clustering.ipynb` for clustering related analysis.

---

## 💡 Insights & Expected Outcomes

- Customer segments based on spending vs income and age  
- Visualization of spending patterns across genders and age groups  
- Clear clusters distinguishing high spenders vs low spenders  
- Recommendations for mall marketing strategy

---

## 📄 License & Credits

- Data source: *Provide the original source of the dataset (if known).*  
- Author: *Name of the project owner or contributors.*  
- If reusing this work, please acknowledge accordingly.
