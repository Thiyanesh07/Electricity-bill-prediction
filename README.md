# ⚡ Electricity Bill Predictor  

This project predicts **electricity bill amounts** based on the number of units consumed using **Machine Learning (Linear Regression)**.  
It helps consumers or utility companies estimate bills from usage data.  

---

## 📌 Project Overview  
- **Dataset:** Electricity_Bill.csv  
- **Goal:** Predict Bill Amount from Units Consumed.  
- Performed **Exploratory Data Analysis (EDA)** to understand data distribution and patterns.  
- Applied **Linear Regression** to build a predictive model.  
- Evaluated the model using regression metrics such as **MSE, RMSE, and R² Score**.  

---

## ⚙️ Requirements  

Make sure you have the following installed:  

- Python 3.8+  
- Jupyter Notebook / JupyterLab  

Install dependencies:  

```
pip install -r requirements.txt
Typical packages used in this project include:

numpy

pandas

matplotlib

seaborn

scikit-learn


```

🛠 Installation & Setup
Clone this repository:

```
git clone https://github.com/Thiyanesh07/electricity-bill-predictor.git
cd electricity-bill-predictor
```


📊 Outcomes


Built a Linear Regression model to predict electricity bill from units consumed.

Evaluation Metrics:

Mean Squared Error (MSE): ~1,110,480

Root Mean Squared Error (RMSE): ~1053.79

R² Score: ~0.0076 (very low → model explains very little variance).

⚠️ This indicates that Units Consumed alone is not enough to accurately predict the bill.
Other features (Rate per Unit, Peak/Off-Peak usage, Region, Customer Type) play a major role.



🖼 Output Images
📌 Linear Regression Plot:







<img width="436" height="344" alt="{674FDE12-2CAF-4DB3-9DE5-3CDFC03ABFEE}" src="https://github.com/user-attachments/assets/b091757b-1e92-414b-af4f-c1367fa69dbf" />










✅ Conclusion
The goal was to predict Electricity Bill Amount from Units Consumed using a simple Linear Regression model.

The model was able to compute predictions, but the low R² value shows weak explanatory power.

This proves that bill amounts depend on multiple factors, not just units consumed.





🔮 Future Scope
Incorporate more features (Rate per Unit, Customer Type, Region, Peak/Off-Peak usage).

Try Polynomial Regression or Tree-based models (Random Forest, XGBoost) for better accuracy.

Deploy as a web app (e.g., Flask/Streamlit) for real-time bill predictions.



📂 Repository Structure
```

ELECTRICITY-BILL-PREDICTOR/
│
│── electricity_bill.ipynb         # Main Jupyter Notebook
│── Electricity_Bill.csv           # Dataset
│── requirements.txt               # Python dependencies
│── README.md                      # Project documentation
```


👨‍💻 Author
Thiyanesh07
