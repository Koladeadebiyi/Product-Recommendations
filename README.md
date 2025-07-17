# Customer Recommendation App

This project is a simple Flask-based customer recommendation system that segments customers and suggests personalized product recommendations.

---

## 📌 Project Structure

Customer_Recommendation_App/
│
├── app.py # Flask application

├── requirements.txt # Dependencies file

├── model/ # Contains data files
│ ├── customer_features.csv
│ ├── top_products_per_cluster.csv
│ ├── purchase_history.csv
│

├── templates/ # HTML templates
│ └── index.html
│

├── venv/ # (Optional) Virtual environment

├── README.md # This file



---

## ✅ Submission Checklist

- [x] `app.py` contains the working Flask application.
- [x] `requirements.txt` lists all required Python dependencies.
- [x] `customer_features.csv`, `top_products_per_cluster.csv`, and `purchase_history.csv` are saved in the `model/` folder.
- [x] `index.html` is in the `templates/` folder with a working user interface.
- [x] Tested locally: run `python app.py` → open [http://127.0.0.1:5000](http://127.0.0.1:5000) → enter Customer ID → see recommendations.


---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Customer_Recommendation_App.git
   cd Customer_Recommendation_App
2. Create a virtula environment
python -m venv venv

3. Activate the virtual environment
venv\Scripts\activate

4.Install dependencies
pip install -r requirements.txt

5. Run the app
python app.py

6. Open the browser and visit
http://127.0.0.1:5000




