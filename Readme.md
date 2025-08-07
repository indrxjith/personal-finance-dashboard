# Here’s the **full, professional-quality `README.md` code** for your personal finance dashboard project.

---

### ✅ `README.md` (copy this and replace your existing one)

```markdown
# 💸 Personal Finance Dashboard

A simple and interactive **Streamlit-based personal finance dashboard** that helps you:
- Upload and categorize your bank transactions
- Visualize your monthly expenses
- Track spending patterns over time
- Edit categories manually using keyword-based rules

---

## 🧾 Features

✅ Upload your bank statement as a CSV  
✅ Automatically categorize transactions based on keywords  
✅ View expense distribution by category  
✅ Time-series analysis of spending  
✅ Manual keyword-based category rules  
✅ Clean, responsive Streamlit UI

---



## 🗂️ Project Structure

```

personal-finance-dashboard/
├── .gitignore
├── README.md
├── requirements.txt
├── main.py
├── categories.json
├── sample\_bank\_statement.csv
└── assets/
└── dashboard\_preview\.png

````

---

## 📂 Sample CSV Format

Make sure your CSV looks like this:

```csv
Date,Description,Amount
2023-08-01,"AMAZON ONLINE", -1500
2023-08-02,"SALARY CREDIT", 50000
2023-08-03,"STARBUCKS", -300
````

> Use your bank's export option and clean it if needed.

---

## ⚙️ Setup Instructions

### 1. Clone the repo

```bash
git clone https://github.com/indrxjith/personal-finance-dashboard.git
cd personal-finance-dashboard
```

### 2. Create virtual environment (optional)

```bash
python -m venv .venv
source .venv/bin/activate       # On Mac/Linux
.venv\Scripts\activate          # On Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the dashboard

```bash
streamlit run main.py
```

---

## 🔧 Customizing Categories

Edit the `categories.json` file to define your own rules:

```json
{
  "Groceries": ["LULU", "CARREFOUR", "SPAR"],
  "Transport": ["UBER", "CAREEM"],
  "Shopping": ["AMAZON", "NOON", "SHEIN"]
}
```

The app will match keywords in the Description to categorize.

---

## 📬 Contributing

Pull requests are welcome! If you have ideas or improvements, feel free to fork and open a PR.

---

## 📄 License

This project is licensed under the MIT License.

```

---

Would you like me to generate:
- A clean `main.py` version?
- Auto-create this folder structure as a zip for upload?
- A better sample CSV?

Let me know what you need next.
```
