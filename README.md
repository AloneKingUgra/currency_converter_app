
# 💱 Currency Converter Web App

A simple and interactive **Currency Converter** built using **Streamlit** and **SQLite3**.  
This web app allows users to easily convert between different world currencies using locally stored exchange rates.

---

## 🌟 Features

- 🔹 Clean and responsive Streamlit-based web interface  
- 🔹 Converts between major world currencies (USD, EUR, GBP, JPY, INR, etc.)  
- 🔹 Uses **SQLite database** to store exchange rates  
- 🔹 Automatically creates and initializes the database if missing  
- 🔹 Instant currency conversion results  
- 🔹 Lightweight and fast — perfect for beginners and student projects  

---

## 🧠 Technologies Used

| Component | Technology |
|------------|-------------|
| Frontend | Streamlit |
| Backend | Python 3.14 |
| Database | SQLite3 |
| Data Handling | Pandas (optional dependency) |

---

## 📁 Project Structure

```

CurrencyConverterApp/
│
├── app.py                # Main Streamlit app
├── currency.db           # SQLite database (auto-created if missing)
└── requirements.txt      # Project dependencies

````

---

## ⚙️ Installation (Run Locally)

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/CurrencyConverterApp.git
cd CurrencyConverterApp
````

### 2️⃣ Create Virtual Environment (optional but recommended)

```bash
python -m venv venv
venv\Scripts\activate     # For Windows
# or
source venv/bin/activate  # For macOS/Linux
```

### 3️⃣ Install Required Packages

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the App

```bash
streamlit run app.py
```

Then open your browser and go to:

```
http://localhost:8501
```

---

## 🚀 Deploy on Streamlit Cloud

You can easily host this project online for **free**:

1. Push all your files to a **GitHub repository**
2. Visit [Streamlit Cloud](https://share.streamlit.io)
3. Click **“New app”** → Select your GitHub repo
4. Choose the branch and `app.py` as the main file
5. Streamlit Cloud will automatically install all dependencies and launch your app 🎉

---

## 🧾 Example Exchange Rates (Preloaded)

| Currency | Rate to INR |
| -------- | ----------- |
| USD      | 83.2        |
| EUR      | 90.5        |
| GBP      | 105.3       |
| JPY      | 0.56        |
| INR      | 1.0         |

*(You can modify or add more currencies directly in the database.)*

---

## 🖼️ Screenshots (optional)

*Add some screenshots of your app here, for example:*
<img width="1911" height="850" alt="image" src="https://github.com/user-attachments/assets/093a6048-7f45-43c4-815e-35f604b8b640" />



## 🧑‍💻 Author

**👨‍🎓 Narasimha**
2nd Year Engineering Student
Project: *Currency Converter using Streamlit and SQLite*

---

## 📜 License

This project is open-source and free to use for educational purposes.

---

## ❤️ Acknowledgements

* [Streamlit Documentation](https://docs.streamlit.io)
* [SQLite Python Docs](https://docs.python.org/3/library/sqlite3.html)
* Inspired by simple and effective UI-based currency converters


