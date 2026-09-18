# 🏡 House Price Prediction & Real Estate Analytics Platform

A Machine Learning-powered real estate analytics platform that predicts residential property prices using historical housing data and advanced predictive modeling. The application is built with **Python, Scikit-Learn, Streamlit, and Plotly**, providing users with real-time property valuation, investment analysis, EMI estimation, future price forecasting, property comparison, and interactive market insights.
-
The project utilizes the *Gradient Boosting Regressor** trained on the King County Housing Dataset to generate accurate house price predictions based on property characteristics such as living area, lot size, bedrooms, bathrooms, construction grade, condition, location, waterfront access, and neighborhood features.

## 🚀 Features.

### 🏠 House Price Prediction
- Predicts house prices in real time.
- Uses 20+ property attributes as input.
- Powered by a trained Gradient Boosting Regressor.

### 📊 Property Classification
Automatically categorizes properties as:
- Budget Property
- Mid-Range Property
- Luxury Property

### ⭐ Property Rating System
Generates a property score based on:
- Construction Grade
- Property Condition
- Scenic View Quality
- Waterfront Availability

### 💡 Investment Analysis
Provides investment recommendations:
- Excellent Investment
- Good Investment
- Moderate Investment
- High-Risk Investment

### 🔮 Future Price Forecasting
- Estimates property value after 5 years.
- Uses appreciation-based forecasting techniques.
- Helps investors evaluate long-term returns.

### 💳 EMI Calculator
Calculates:
- Monthly EMI
- Loan Amount
- Down Payment
- Total Interest Payable

### ⚖️ Property Comparison
- Save multiple predictions.
- Compare properties side-by-side.
- Evaluate investment opportunities efficiently.

### 📈 Market Insights Dashboard
Interactive visualizations using Plotly:
- House price distribution
- Living area vs price analysis
- Grade-wise pricing trends
- Location-based insights

### 📥 Downloadable Reports
Export prediction details including:
- Estimated property value
- Investment recommendation
- Property specifications
- Financial calculations

### 🎨 Modern User Interface
Built using Streamlit with:
- Responsive layout
- Sidebar-based input controls
- Interactive tabs
- Dynamic charts and visualizations

---

## 🛠️ Technology Stack

| Category | Technologies |
|-----------|-------------|
| Programming Language | Python |
| Machine Learning | Scikit-Learn |
| Data Processing | Pandas, NumPy |
| Web Framework | Streamlit |
| Visualization | Plotly |
| Model Serialization | Pickle |
| Dataset | King County Housing Dataset |

---

## 📂 Project Structure

```text
house-price-prediction/
│
├── app.py                    # Main Streamlit Application
├── train_model.py            # Model Training Script
├── model.pkl                 # Trained ML Model
├── kc_house_data.csv         # Housing Dataset
├── housesales.py             # Data Analysis Script
├── housesales.ipynb          # Jupyter Notebook
├── README.md                 # Project Documentation
└── run file.txt              # Execution Instructions
```

---

## 📊 Dataset Information

The project uses the **King County Housing Dataset**, which contains real estate transactions and property characteristics.

### Features Used

- Sale Date
- Bedrooms
- Bathrooms
- Floors
- Waterfront
- View Rating
- Condition
- Grade
- Square Foot Living Area
- Square Foot Lot Area
- Basement Area
- Year Built
- Year Renovated
- Zipcode
- Latitude
- Longitude
- Nearby Living Area
- Nearby Lot Area

### Target Variable

- House Price

---

## 🧠 Machine Learning Model

### Algorithm Used
**Gradient Boosting Regressor**

### Why Gradient Boosting?
- High prediction accuracy
- Handles complex non-linear relationships
- Robust against overfitting
- Excellent performance on tabular datasets

### Training Process

1. Load housing dataset.
2. Preprocess features.
3. Convert date information into numerical format.
4. Split dataset into training and testing sets.
5. Train Gradient Boosting Regressor.
6. Evaluate model performance.
7. Save trained model using Pickle.

---

## 🔄 Workflow

```text
Housing Dataset
       │
       ▼
Data Preprocessing
       │
       ▼
Feature Engineering
       │
       ▼
Model Training
       │
       ▼
Gradient Boosting Regressor
       │
       ▼
Model Serialization (model.pkl)
       │
       ▼
Streamlit Web Application
       │
       ▼
Real-Time Predictions
       │
       ├── Property Rating
       ├── Investment Analysis
       ├── EMI Calculation
       ├── Future Forecast
       └── Market Insights
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/your-username/house-price-prediction.git
cd house-price-prediction
```

### Install Dependencies

```bash
pip install pandas numpy scikit-learn streamlit plotly
```

### Train the Model

```bash
python train_model.py
```

### Launch the Application

```bash
streamlit run app.py
```

---

## 🎯 Use Cases

- Real Estate Valuation
- Property Investment Analysis
- Mortgage Planning
- Housing Market Research
- Data Science Learning
- Machine Learning Demonstration Projects
- Property Comparison and Decision Support

---

## 📈 Future Enhancements

- Integration with live real-estate APIs
- Advanced forecasting models
- Deep Learning-based price prediction
- Geographic heatmaps
- User authentication system
- Cloud deployment support
- Recommendation engine for buyers

---

## 👨‍💻 Project Highlights

- End-to-End Machine Learning Pipeline
- Interactive Streamlit Dashboard
- Real Estate Analytics
- Financial Planning Tools
- Data Visualization with Plotly
- Practical Business Use Case
- Industry-Relevant ML Application

---

## 📜 License

This project is intended for educational and learning purposes. Feel free to modify and extend it for personal or academic use.
