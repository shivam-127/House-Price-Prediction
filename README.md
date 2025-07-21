# 🏠 Simple House Price Predictor

This is a **Streamlit-based web app** that predicts house prices based on square footage using a **Linear Regression model** trained on synthetic data. It's ideal for understanding how size impacts pricing and for demonstrating basic regression modeling.

🔗 **Live Demo**: [Click to Launch App](https://urban-adventure-jjq5gppgjgj7fp595-8501.app.github.dev/)

---

## 📌 About the Project

This app demonstrates a **simple yet effective machine learning model** that:

* Uses synthetic data to simulate house sizes and prices
* Trains a **Linear Regression** model every time the app runs
* Takes **user input for house size** and predicts the estimated price
* Displays a dynamic **scatter plot** with the prediction point

---

## 🧠 Model Description

* **Algorithm**: Linear Regression
* **Data**: Synthetic data generated with Gaussian noise
* **Feature**: `size_sqft` (House size in square feet)
* **Target**: `price` (in dollars)
* **Libraries**:

  * `pandas`
  * `numpy`
  * `scikit-learn`
  * `streamlit`
  * `plotly`

---

## 📺 App Features

* 📏 Input house size (500–5000 sq. ft.)
* 📈 Predict price using trained regression model
* 📊 Visualize prediction point against generated dataset
* 💡 Simple and clean user interface

---

## 📂 Project Structure

```
.
├── app.py               # Streamlit application file
├── README.md            # Documentation
└── requirements.txt     # Python dependencies
```

---

## ▶️ How to Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/shivam-127/House-Price-Prediction.git
   cd house-price-predictor
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch the Streamlit app:

   ```bash
   streamlit run app.py
   ```

---

## 📦 Example Usage

Enter a square footage like `1500`, click on **Predict Price**, and the app will:

* Display the predicted price (e.g., `$151,532.47`)
* Show the point in red on a scatter plot against training data

---

## 📬 Contact

Created by Shivam. Feel free to connect for questions, feedback, or collaboration.

---

## 📝 License

This project is for educational/demonstration purposes. You may modify and reuse with proper attribution.
