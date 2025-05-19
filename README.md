
---

# 🇳🇬 Banditry Prediction in Nigeria: A Data Mining Approach

## 📌 Project Overview

This project applies **data mining and machine learning** to predict and prevent **banditry incidents across Nigeria**, addressing a key national security concern. Using over **29,000 crime records** from **ACLED**, **HDX**, and the **World Bank**, the study follows the **CRISP-DM** methodology to:

* Analyze spatial, temporal, and socioeconomic patterns.
* Cluster Nigerian states based on risk levels.
* Predict LGA-level banditry incidents with 98% accuracy.
* Interpret key crime drivers using SHAP.

> 🔗 **Explore the Full Analysis Notebook**:
> [View on NBViewer](https://nbviewer.org/github/AkinwandeSlim/NG-Banditry-Analysis/blob/main/DataMIning%28CRIME%20EVENTS%29-2.ipynb)

---

## 🚀 Features

* ✅ **Data Preprocessing**: Integrates crime, poverty, population, and location data.
* 📊 **Exploratory Data Analysis**: Visual insights into trends and spatial distributions.
* 🧠 **Clustering (K-Means)**: Groups 37 states into high-, medium-, and low-risk.
* 🔮 **LGA-Level Prediction**: XGBoost model (R² = 0.98) forecasts future incidents.
* 📌 **Model Interpretability**: SHAP explains top drivers (e.g., historical crime, poverty).
* 🗺️ **Visualizations**: Choropleths, scatter plots, bar charts, and SHAP plots.

---

## 📈 Key Findings

* **High-Risk States**: Borno (4,705+ incidents), Kaduna, Zamfara, Katsina, Niger.
* **Hotspot LGAs**: Maiduguri, Gusau, and Katsina show extreme risk.
* **Core Drivers**: Poverty and deprivation are leading socioeconomic enablers.
* **Model Accuracy**: XGBoost achieves 98% predictive accuracy (5-fold CV validated).

---

## 🧰 Installation & Setup

### 🔧 Prerequisites

* RAM: **8GB minimum** (16GB recommended)
* CPU: **4 cores**
* Disk: **50GB+ free**
* Python: **3.10+**

### 📥 Setup Instructions

```bash
# Clone the Repository
git clone https://github.com/your-username/banditry-prediction-nigeria.git
cd banditry-prediction-nigeria

# Create a Virtual Environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install Dependencies
pip install -r requirements.txt
```

> **Required Packages**:
> `pandas`, `scikit-learn`, `xgboost`, `shap`, `matplotlib`, `seaborn`, `geopandas`, `jupyter`

### 📂 Data Preparation

1. Download data from:

   * [ACLED](https://acleddata.com/)
   * [HDX (Poverty)](https://data.humdata.org/)
   * [World Bank (Population)](https://databank.worldbank.org/)
2. Place all files into the `data/` folder.

---

## 💻 Usage

```bash
jupyter notebook
```

1. Open `DataMIning(CRIME EVENTS)-2.ipynb`
2. Run cells in sequence:

   * Data preprocessing
   * EDA & clustering
   * Predictive modeling
   * Visualizations & SHAP analysis
3. Save all outputs (charts, CSVs) to the `outputs/` folder.

---

## 📂 Project Structure

```
banditry-prediction-nigeria/
├── data/                          # Input datasets
├── outputs/                       # Generated maps, plots, CSVs
├── DataMIning(CRIME EVENTS)-2.ipynb  # Main analysis notebook
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation
```

---

## 📊 Visual Highlights

* 🔵 **Scatter**: Crime rate vs. poverty rate per state
* 🗺️ **Map**: State risk clustering (choropleth)
* 📈 **Bar**: XGBoost feature importance
* 🧠 **SHAP**: Summary plot of top predictive drivers

---

## 🤝 Contributing

Contributions are welcome!
To contribute:

```bash
# Fork and create a branch
git checkout -b feature-name

# Commit and push
git commit -m 'Add new feature'
git push origin feature-name
```

Then open a **pull request**.

---

## 📜 License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.

---

## 📬 Contact

* **📧 Email**: [alexdata2022@gmail.com](mailto:alexdata2022@gmail.com)
* **🔗 LinkedIn**: [www.linkedin.com/in/akinwandealex](https://www.linkedin.com/in/akinwandealex)

---

## 🙏 Acknowledgments

* **Data**: [ACLED](https://acleddata.com/), [HDX](https://data.humdata.org/), [World Bank](https://databank.worldbank.org/)
* **Frameworks**:

  * Situational Crime Prevention (Clarke, 1997)
  * Situational Action Theory (Wikström, 2006)
* **Tools**: Python, Jupyter, pandas, scikit-learn, XGBoost, SHAP, GeoPandas

---

