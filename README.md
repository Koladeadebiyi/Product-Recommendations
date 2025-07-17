# Customer Recommendation App

This project is a simple Flask-based customer recommendation system that segments customers and suggests personalized product recommendations.

---

## 📌 Project Structure

Project Folder Includes:

app.py — Flask application Python script.

requirements.txt — List of Python dependencies.

templates/ — Folder containing index.html (the frontend template).

model/ — Folder with:

customer_features.csv

top_products_per_cluster.csv

purchase_history.csv (if used)

static/ — (Optional) CSS or image files if you styled the HTML.

## 📌 Requirements.txt
Flask==2.3.2
pandas==1.5.3
numpy==1.23.5
scikit-learn==1.2.2



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
   git clone https://github.com/koladeadebiyi/Customer_Recommendation_App.git
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




