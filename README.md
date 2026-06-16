# Minor-Project-2
<img width="2000" height="1000" alt="image" src="https://github.com/user-attachments/assets/018294d9-4796-41ee-8636-2e221d7a62d2" />
# 🩺 Healtho – AI Healthcare Chatbot

**Healtho** is a smart, virtual health assistant powered by a Machine Learning Decision Tree model. It provides users with a clean, interactive web interface to check symptoms, receive potential medical diagnoses, and view doctor consultation risk scores.

---

## 🌟 Features

* 💬 **Interactive Symptom Checker** – Answer simple Yes/No questions about how you feel.
* 🧠 **Machine Learning Diagnosis** – Uses a Decision Tree classifier trained on real healthcare data to predict potential diseases.
* 🚨 **Risk Assessment** – Calculates risk percentage and advises whether an immediate doctor consultation is necessary.
* 🌐 **Modern Web Interface** – A clean, responsive UI built with Streamlit.

---

## 🛠️ Technologies Used

* **[Python](https://www.python.org/)** – Core programming language.
* **[Streamlit](https://streamlit.io/)** – Used to build the modern interactive web application frontend.
* **[Scikit-Learn](https://scikit-learn.org/)** – Powers the `DecisionTreeClassifier` machine learning model.
* **[Pandas](https://pandas.pydata.org/) & [NumPy](https://numpy.org/)** – Data manipulation, processing, and handling the `.csv` datasets.

---

## 🚀 How to Run Locally

### 1. Prerequisites
Ensure you have Python installed. It is recommended to use a virtual environment.

### 2. Install Dependencies
Install all required libraries using `pip`:
```bash
pip install -r requirements.txt
```

### 3. Start the Web App
Run the Streamlit server:
```bash
streamlit run app.py
```

### 4. Open in Browser
The application will automatically open in your default browser at `http://localhost:8501`.

---

## 🏗️ System Architecture
You can view the system architecture diagram in the root of this project: `Healtho_System_Architecture.png`.

---

## 📄 License

This project is open-source under the [MIT License](LICENSE).

