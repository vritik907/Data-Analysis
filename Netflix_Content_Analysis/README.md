# Netflix Content Analysis

This project explores Netflix’s content dataset to uncover patterns and insights around content release years, dates added to Netflix, descriptions (word usage), and more.

---

## 🛠 Features & Analysis

Here are some of the analyses and visualizations included:

- Trends between **release year** vs **year content was added** to Netflix — seeing delay patterns or how old content gets added.  
- Word-level analysis of descriptions:  
  - Aggregating all descriptions into one string.  
  - Identifying most common word pairs (bigrams) in descriptions.  
- Visualizations like heatmap, hexbin, scatter / bubble plots to display densities and trends.

---

## 🚀 Getting Started

### Prerequisites

- Python 3.7+  
- Jupyter Notebook or JupyterLab  
- Required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `nltk` (for text processing), etc.

### Installation & Setup

1. Clone this repository:
   ```
   git clone https://github.com/vritik907/Data-Analysis.git
   ```

2. Navigate to the project folder:
   ```
   cd Data-Analysis/Netflix_Content_Analysis
   ```

3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Load the dataset (`netflix_titles.csv`) located in the `data/` folder and run the notebooks in `notebooks/`.

---

## 📁 Data Source

- **Dataset:** `netflix_titles.csv` — includes metadata like title, type (movie/tv show), release year, date added, description, etc.

---

## 🔍 How to Use

- To reproduce analyses, run the notebooks in order:
  1. `data_cleaning.ipynb`  
  2. `EDA_release_year.ipynb`  
  3. `description_analysis.ipynb`

- Visualizations will save automatically (or can be exported) using matplotlib/seaborn setup in notebooks.

---

## 💡 Findings (Highlights)

- There are noticeable patterns in how long after release content typically gets added to Netflix.  
- Older movies often have large delays before being added.  
- Frequent bigrams in descriptions include terms like *based on*, *original series*, etc., highlighting typical themes in content descriptions.

---

## 🔗 Download / Clone Link

You can download or clone this repository using:

```
https://github.com/vritik907/Data-Analysis.git
```

Or directly download ZIP:

[Download ZIP](https://github.com/vritik907/Data-Analysis/archive/refs/heads/main.zip)

---

## 📄 License

Specify your license here (e.g., MIT, Apache 2.0). If none, you may add one.

---

## 👤 Author

- **Vritik907** — for queries / suggestions, refer to the GitHub profile.
