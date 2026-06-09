# AlSiMg-ML-Alloy
Python code and raw experimental data for CatBoost modeling, SHAP/PDP analysis, and multi-objective optimization of cast Al-Si-Mg alloys.


---

## 📄 File Description

1.  **`data.csv`**
    Raw experimental dataset, including alloy composition and mechanical property data (elongation `EL` and ultimate tensile strength `UTS`).

2.  **`CatBoost Model.ipynb`**
    Main model training notebook:
    - CatBoost model training for predicting EL and UTS
    - Model evaluation metrics
    - SHAP analysis

3.  **`PDP for EL.ipynb`**
    Partial Dependence Plot (PDP) analysis for elongation (`EL`), showing how each feature affects ductility.

4.  **`PDP for UTS.ipynb`**
    Partial Dependence Plot (PDP) analysis for ultimate tensile strength (`UTS`), showing how each feature affects strength.

---

## ▶️ Recommended Running Order
To reproduce the results, please run the notebooks in this order:
1.  `CatBoost Model.ipynb`
2.  `PDP for EL.ipynb`
3.  `PDP for UTS.ipynb`

---

## ⚙️ Environment Setup
Python >= 3.8 is required.

Install dependencies:
```bash
pip install -r requirements.txt



---

### ✅ requirements.txt`（直接复制）
```txt
numpy
pandas
catboost
shap
matplotlib
scikit-learn
