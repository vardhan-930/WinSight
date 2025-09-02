# DealClosureFirm

AI-powered system to **predict deal closures** based on a company's **past sales performance**.

This project helps sales teams forecast which opportunities are most likely to close by analyzing historical deal data from CRMs (Salesforce, HubSpot, Dynamics, etc.).  
It uses machine learning models to discover patterns in past deals (won/lost) and predicts success probabilities for new deals.

---

## 🚀 Features
- 📊 **Data Preprocessing** – Clean and prepare historical CRM deal data.
- 🧠 **Machine Learning Models** – Logistic Regression, Random Forest, XGBoost/LightGBM.
- 📈 **Win Probability Prediction** – Estimate chances of closing new opportunities.
- 🔍 **Feature Insights** – Understand what drives wins/losses (deal size, stage, industry, etc.).
- 📂 **CRM Integration Ready** – Can connect with Salesforce or HubSpot.
- 📊 **Visualization Dashboard** – Interactive charts for deal predictions & feature importance.

---

## 📦 Tech Stack
- Python (pandas, scikit-learn, xgboost, lightgbm)
- Jupyter Notebook (for EDA & model training)
- Flask / FastAPI (for REST API deployment)
- Streamlit / Plotly (for dashboards)
- PostgreSQL / MySQL (optional for data storage)

---

## 📊 Dataset Example
Example CSV structure:

| Deal_ID | Deal_Size | Industry | Region | Stage | Sales_Rep | Duration_Days | Outcome |
|---------|-----------|----------|--------|-------|-----------|---------------|---------|
| 101     | 50,000    | IT       | APAC   | Proposal Sent | Alice | 45            | Won     |
| 102     | 20,000    | Finance  | US     | Negotiation   | Bob   | 30            | Lost    |

---

## 🔧 Installation
```bash
# Clone repo
git clone https://github.com/yourusername/DealClosureFirm.git
cd DealClosureFirm

# Create virtual environment
python -m venv venv
source venv/bin/activate   # (Linux/Mac)
venv\Scripts\activate      # (Windows)

# Install dependencies
pip install -r requirements.txt
