# 🧠 ANN to Model the Impact of Economic Openness on Political Stability (1996–2021)

This project tests a classic assumption in political science: **Does greater economic and financial openness improve a country's political stability?**  
To explore this, I use an Artificial Neural Network regressor trained on global data from 1996 to 2021.

---

## 📊 About the Data

The dataset was compiled from:

- **World Bank Open Data**
- **Worldwide Governance Indicators (WGI)**  
  https://www.worldbank.org/en/publication/worldwide-governance-indicators

**Variables included:**

- **Country**  
- **Country Code** (ISO abbreviation)  
- **Year** (1996 → 2021)  
- **Stability Score**  
  - Aggregate WGI measure from **0 (less stable)** to **100 (more stable)**
- **FDI % GDP**  
  - Foreign Direct Investment as % of national GDP  
- **Trade % GDP**  
  - Total trade volume (exports + imports) as % of national GDP  

---

## 🧪 What the Model Does

The notebook trains an **Artificial Neural Network (ANN) regressor** to estimate the correlation between openness variables (FDI and Trade) and changes in political stability.  
The goal is to see whether economic integration consistently predicts more stable governance.

---

## 💻 Running the Project

Before running the notebook, make sure the required Python packages are installed:

```bash
pip install pandas numpy matplotlib scikit-learn tensorflow
)
