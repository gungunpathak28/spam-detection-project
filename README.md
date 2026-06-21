# 📩 Spam Detection System

A Machine Learning based web application that classifies messages as **Spam** or **Ham (Not Spam)**.

----

## 🚀 Features
- Detects spam messages instantly
- Simple and user-friendly UI
- Machine Learning model integration
- Real-time prediction using trained model

----

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS
- **Backend:** Python (Flask)
- **Machine Learning:** Scikit-learn
- **Libraries:** Pandas, NumPy, Pickle

----

## 📂 Project Structure
spam-detection-project/
│── static/ # CSS, JS files
│── templates/ # HTML files
│── app.py # Main Flask app
│── train_model.py # Model training
│── model.pkl # Trained model
│── vectorizer.pkl # Text vectorizer
│── requirements.txt # Dependencies


---

## ⚙️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/gungunpathak28/spam-detection-project.git
cd spam-detection-project
2. Install dependencies
pip install -r requirements.txt

3. Run the application
python app.py
4. Open in browser
http://127.0.0.1:5000

🧠 How it Works
Input message is taken from user
Text is cleaned and processed
Converted into numerical form using vectorizer
Model predicts → Spam or Ham
<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/6aa64fee-7dee-48d9-bc57-aaf802856b1b" />



