# 📊 COVID-19 Government Policy Impact Analysis

This project presents a comprehensive analysis of **government responses to COVID-19** (Jan–Oct 2020) across **228 countries**. Using **exploratory data analysis, panel regression, clustering, and machine learning models (XGBoost + SHAP, PCA)**, we evaluated how policy interventions affected COVID-19 cases and deaths, ranked their effectiveness, and compared country-level responses.

---

## 🚀 Key Highlights
- **Exploratory Data Analysis (EDA)**: Trends in cases, deaths, and policy adoption across regions.  
- **Panel Regression**: Quantified delayed effects of policies on cases and deaths after controlling for multicollinearity.  
- **Clustering (K-Means + PCA)**: Identified two distinct clusters of pandemic responses — severe outbreaks with strict measures vs. moderate outbreaks with lighter measures.  
- **Policy Adoption Analysis**: Logistic regression & survival analysis showed how fiscal space and safety nets influenced wage support adoption speed.  
- **Policy Stringency Classification**: Classified responses into Low, Medium, High stringency using ensemble models (Logistic Regression, Decision Tree, Gradient Boosting).  
- **Policy Ranking (XGBoost + SHAP)**:  
  - *Cases*: Mask mandates, travel restrictions, and school closures were most impactful.  
  - *Deaths*: Domestic travel bans and mass gathering bans were strongest.  
- **Country Ranking**:  
  - *Most effective responses*: Morocco, Thailand, Colombia, Italy, Spain.  
  - *Severe impact*: USA, India, Brazil, Mexico, UK.  

---

## 🛠️ Tech Stack
- **Python** (Pandas, NumPy, Scikit-learn, Statsmodels)  
- **XGBoost & SHAP** for feature importance and interpretability  
- **PanelOLS (linearmodels)** for regression  
- **Clustering (K-Means + PCA)**  
- **Matplotlib / Seaborn** for visualization  

---

## 📂 Project Structure
    data/             # Raw and processed datasets
    notebooks/        # Jupyter notebooks with EDA and modeling
    src/              # Scripts for regression, clustering, ranking
    results/          # Visualizations and analysis outputs
    README.md         # Documentation

---

## 📈 Results Snapshot
- Domestic restrictions **significantly reduced cases**.  
- Economic support correlated with **higher cases and deaths** (likely due to increased mobility or reverse causality).  
- High-stringency countries generally fared better, but enforcement & healthcare capacity mattered.  
- PCA-based **Effectiveness and Severity Scores** allowed meaningful cross-country comparisons.  

---

## 📌 Future Work
- Extend dataset beyond Oct 2020 to include vaccination phase.  
- Apply causal inference methods (DiD, IV regression) for stronger policy impact estimates.  
- Build interactive dashboards for policy effectiveness comparison.  

---

## 👥 Authors
- **Mudavath Shashank Chauhan**  
- **Chandra Sailesh**  

---

## 📜 License
This project is licensed under the MIT License.  

---

## 🔗 References
- [XGBoost Documentation](https://xgboost.readthedocs.io/)  
- [SHAP Documentation](https://shap.readthedocs.io/)  
- Hale, T. et al. (2021). *Oxford COVID-19 Government Response Tracker (OxCGRT)*.  
