# ✈️ Flight Landing Time Predictor

A simple and interactive web application that predicts the estimated landing time of a flight based on various inputs such as departure time, distance, departure delay, and taxi times. The prediction is powered by a machine learning model trained using Linear Regression.

---

## 🚩 Features

- Predicts flight landing time based on user inputs
- User-friendly interface
- Fast and real-time predictions in the browser
- Converts **HHMM** input time to readable **HH:MM** landing time format
- Responsive design with a modern look

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Machine Learning Model:** Python (scikit-learn - Linear Regression)
- **Deployment:** Fully client-side (no server needed)

---

## 📈 Machine Learning Overview

The model was trained using synthetic flight-related data, including:
- Distance (in miles)
- Departure delay (in minutes)
- Taxi-out time (in minutes)
- Taxi-in time (in minutes)

The model was trained using **Linear Regression** and the intercept and coefficients were directly integrated into the JavaScript file for real-time client-side predictions.

---

## 🎯 How to Use

1. Clone or download the project files.
2. Open the `index.html` file in your browser.
3. Enter the required flight details:
   - Departure time (in **HHMM** format)
   - Distance (in kilometers)
   - Departure delay (in minutes)
   - Taxi-out time (in minutes)
   - Taxi-in time (in minutes)
4. Click on **"Predict Landing Time"**.
5. The estimated landing time will be displayed below the form.

---

## 📂 Folder Structure

```
/flight-landing-time-predictor
├── index.html      # Frontend form and structure
├── style.css       # Styling for the page
├── script.js       # JavaScript logic for prediction
├── model_training.py # Python ML model training script (for generating model params)
└── README.md       # Project documentation
```

---

## ⚠️ Notes

- The model is trained using **miles** internally but accepts **kilometers** on the frontend for user convenience.
- This is a demonstration project using synthetic data; real-world accuracy may vary.
- Model parameters (intercept & coefficients) were integrated directly into the frontend for a lightweight solution.

---

## 🚀 Future Enhancements

- Integrate with a backend (Flask/Django/Node) for dynamic model updates
- Improve model with real-world flight datasets
- Add time zone and date considerations for international flights
- Mobile-optimized design

---

## 👨‍💻 Author

- **Harish R** - Artificial Intelligence & Data Science Enthusiast
- **Gurucharan Raj K** -Artificial Intelligence & Data Science Enthusiast 
---
