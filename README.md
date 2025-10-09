# 🚗 ML-Powered used Car Price Prediction Web App 

![Python](https://img.shields.io/badge/Python-3.11-blue) ![Flask](https://img.shields.io/badge/Flask-2.3.2-orange) ![HTML5](https://img.shields.io/badge/HTML5-orange) ![CSS3](https://img.shields.io/badge/CSS3-blue) ![License](https://img.shields.io/badge/License-MIT-green)

A **Machine Learning-powered web application** that predicts the **selling price of used cars**. Users can input car details such as year, showroom price, kilometers driven, ownership, fuel type, seller type, and transmission to get an instant prediction.

---

## 🌟 Features

- Interactive **form-based UI** with dropdowns and input fields.
- **Dark theme** with glowing accents for a futuristic look.
- **Responsive design** for mobile and desktop screens.
- Highlights prediction results in a dedicated, visually appealing container.
- Powered by a **trained ML model** for accurate predictions.

---

## 🛠 Tech Stack

| Layer            | Technology                  |
|------------------|-----------------------------|
| Backend          | Python, Flask               |
| Frontend         | HTML, CSS                   |
| Machine Learning | Scikit-learn / Pickle model |
| Deployment       | Render                      |

---

## 📂 Folder Structure
```text
CARPRICEPREDICTION/
├── app.py # Flask backend
├── templates/
│ └── index.html # Frontend HTML template
├── static/
│ └── style.css # External CSS
├── screenshots/
│ └── app.png 
│ └── result.png 
├── model/
│ └── random_forest_regression_model.pkl # Pre-trained ML model
├── requirements.txt # Python dependencies
└── README.md
```

### 🎯 Usage

1. Fill out the form:
   - **Year**
   - **Showroom Price (in lakhs)**
   - **Kilometers Driven**
   - **Previous Owners (0, 1, or 3)**
   - **Fuel Type**
   - **Seller Type**
   - **Transmission Type**

2. Click the **`Calculate the Selling Price`** button.

3. Your predicted price will appear below the form in a highlighted box.

