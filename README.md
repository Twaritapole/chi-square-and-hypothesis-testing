# chi-square-and-hypothesis-testing
# 📊 Hypothesis Testing Assignments

This repository contains Python implementations of **statistical hypothesis testing** exercises, covering both categorical and numerical data analysis.

---

## 🔹 Tasks Covered

### 1. Chi-Square Test – Association between Device Type and Customer Satisfaction
- **Objective**: Determine whether customer satisfaction level is associated with the type of smart home device purchased (Smart Thermostat vs. Smart Light).  
- **Steps**:
  - State Null and Alternative Hypotheses
  - Compute Chi-Square statistic
  - Find Critical Value at α = 0.05
  - Compare & conclude  
- **Dataset**: Customer satisfaction contingency table (600 total observations).

### 2. Hypothesis Testing – Weekly Operating Cost Model
- **Scenario**: A franchise model claims weekly operating cost follows the model `W = $1,000 + 5X`.  
- **Given**:
  - Sample size = 25 restaurants
  - Sample mean = Rs. 3,050
  - Units produced (X) = 600
  - σ = 5 × 25 = 125
- **Steps**:
  - State hypotheses (H₀ and H₁)
  - Calculate test statistic (Z)
  - Determine critical value at α = 0.05
  - Decision: Reject / Fail to reject H₀
  - Conclusion: Is there evidence that costs are higher than model suggests?

---

## 📂 Repository Structure
- `notebooks/` → Jupyter notebooks with full analysis  
- `scripts/` → Python scripts implementing statistical tests  
- `data/` → CSV files (optional; contingency tables or simulated data)  
- `results/` → Output summaries  

---

## 🚀 Tools & Libraries
- Python: NumPy, Pandas, SciPy, Statsmodels
- Jupyter Notebook
- Matplotlib / Seaborn (for visualization)

---

## ✅ Example Results

### Chi-Square Test
- χ² statistic ≈ (calculated in notebook)  
- Critical Value (df = 4, α = 0.05) ≈ 9.488  
- Decision: Reject/Fail to Reject H₀ (based on comparison)  

### Hypothesis Test (Cost Model)
- Z statistic ≈ (calculated in notebook)  
- Critical Value (α = 0.05) = 1.645 (one-tailed test)  
- Conclusion: Evidence supports/does not support owners’ claim.

---

## 🔮 Future Scope
- Extend hypothesis testing with ANOVA and regression-based tests  
- Simulate larger datasets for robustness checks  
- Automate tests into a reusable statistical testing framework
