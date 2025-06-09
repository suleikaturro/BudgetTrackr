# BudgetTrackr – Personal Finance Dashboard

**BudgetTrackr** is a Streamlit-based personal finance web application that helps users track income, manage expenses, visualize financial behavior, and monitor savings goals. All through an interactive and user-friendly interface.

---

##  Features

-  Upload transaction CSVs
-  Convert amounts with real-time exchange rates (via ExchangeRate-API)
-  Visualize spending by category
-  Track monthly savings progress
-  View transaction locations on a map
-  Fully interactive layout with Streamlit widgets

---
## How to Run:

🔧 How to Run
1. Clone the repo and navigate to the project folder

git clone https://github.com/suleikaturro/BudgetTrackr.git
cd BudgetTrackr

2. Install the dependencies

pip install -r requirements.txt

3. (Optional) Add your ExchangeRate API key for currency conversion

Create a file named .streamlit/secrets.toml and paste in your API key:

EXCHANGE_API_KEY = "your_api_key_here"

    Get a free key from https://www.exchangerate-api.com

4. Run the Streamlit app

streamlit run app/dashboard.py

