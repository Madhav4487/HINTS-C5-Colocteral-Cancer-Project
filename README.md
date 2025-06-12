## 🧪 Project Overview: Colorectal Cancer Screening Behavior Analysis

This project analyzes behavioral and demographic factors that influence colorectal cancer screening adherence. The analysis uses publicly available data from the **Health Information National Trends Survey (HINTS)**, conducted by the National Cancer Institute.

---

### 📊 Dataset

- **Source**: [National Cancer Institute - HINTS](https://hints.cancer.gov)
- **Cycles Used**: HINTS 5, Cycle 2, Cycle 3, and Cycle 4
- **Data Preparation**:
  - Appended the three survey cycles into a single dataset
  - Removed duplicate records and weight variables
  - Applied correlation filtering: variables with pairwise correlation > 0.90 were reviewed, and one of each highly correlated pair was removed

---

### ⚙️ Methodology

- **Modeling Techniques**:
  - Logistic Regression
  - Random Forest Classifier
- **Feature Importance**:
  - Used SHAP (SHapley Additive exPlanations) values from the Random Forest model
  - Selected the **top 15 most important features** influencing screening behavior

---

### 🧠 Key Findings

- **Demographic factors** such as **age** are dominant predictors of screening adherence
- **Digital health literacy** factors like:
  - **Internet access**
  - **Use of digital devices for health information**
  
  play a significant role in colorectal cancer screening behavior

---

### 📌 Conclusion

Improving access to digital resources and addressing demographic disparities can enhance colorectal cancer screening adherence. These insights are valuable for designing targeted public health interventions.

### 🔮 Future Work

- **Expand to More HINTS Cycles**: Incorporate additional HINTS cycles (e.g.,HINTS4) to increase sample size and improve generalizability across time.
- **Temporal Analysis**: Investigate trends over time in screening behavior and digital literacy using longitudinal techniques.
- **Deep Learning Models**: Explore deep learning methods (e.g., neural networks or autoencoders) for nonlinear pattern recognition in screening behaviors.
- **Explainability Comparison**: Compare SHAP with other explainability techniques (e.g., LIME, permutation importance) to validate feature importance.
- **Subgroup Analysis**: Analyze screening behavior within key subpopulations (e.g., rural vs. urban, insured vs. uninsured, age groups).
- **Policy Simulation**: Model the potential impact of digital health access interventions on screening rates using causal inference or simulation methods.
- **Interactive Dashboard**: Develop a public-facing dashboard (e.g., with Streamlit or Power BI) to visualize screening adherence by demographics and digital access.

  
## 📬 Contact

**Madhav Dahal**  
📧 madhavdahal16@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/madhav-dahal-ms-9a1147b0)  
🔗 [GitHub](https://github.com/Madhav4487)
