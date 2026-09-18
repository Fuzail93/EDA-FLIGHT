# ✈️ Flight Price Prediction | Exploratory Data Analysis (EDA) & Feature Engineering

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-orange?style=for-the-badge&logo=pandas" />
  <img src="https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?style=for-the-badge&logo=numpy" />
  <img src="https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?style=for-the-badge&logo=scikitlearn" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter" />
</p>

---

# 📖 Project Overview

This project performs **Exploratory Data Analysis (EDA)** and **Feature Engineering** on a Flight Price dataset to prepare it for machine learning.

The notebook demonstrates a complete preprocessing workflow including cleaning, handling missing values, extracting useful date and time features, encoding categorical variables, and transforming raw data into a format suitable for predictive modeling.

---

# 🎯 Project Objectives

- Explore the Flight Price dataset
- Perform data cleaning
- Handle missing values
- Extract useful date & time features
- Encode categorical variables
- Prepare data for Machine Learning
- Understand relationships between flight features and ticket prices

---

# 📂 Dataset Information

**Dataset:** `flight_price.xlsx`

The dataset contains airline booking information including:

- Airline
- Date of Journey
- Source
- Destination
- Route
- Departure Time
- Arrival Time
- Duration
- Total Stops
- Additional Information
- Ticket Price (Target Variable)

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Jupyter Notebook

---

# 📊 Exploratory Data Analysis

The notebook includes:

- Dataset Overview
- Dataset Shape
- Column Information
- Data Types
- Descriptive Statistics
- Missing Value Analysis
- Feature Inspection
- Data Cleaning
- Feature Engineering

---

# ⚙️ Feature Engineering

The following preprocessing techniques were applied:

## 📅 Date Features

- Extracted Journey Day
- Extracted Journey Month
- Removed original Date_of_Journey column

---

## 🕒 Departure Time

- Departure Hour
- Departure Minute

---

## 🕓 Arrival Time

- Arrival Hour
- Arrival Minute

---

## ⏳ Duration

Converted duration into:

- Duration Hours
- Duration Minutes

---

## 🛑 Total Stops

Converted categorical values into numerical format.

| Stops | Encoded Value |
|--------|--------------:|
| Non-stop | 0 |
| 1 Stop | 1 |
| 2 Stops | 2 |
| 3 Stops | 3 |
| 4 Stops | 4 |

---

## 🔄 Categorical Encoding

Applied **One-Hot Encoding** on categorical columns:

- Airline
- Source
- Destination

This converts categorical variables into numerical features for Machine Learning models.

---

# 📁 Project Structure

```
EDA_FLIGHT/
│
├── Flight_EDA.ipynb
├── flight_price.xlsx
├── README.md
```

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/Fuzail93/EDA-FLIGHT.git
```

---

## Navigate to Project

```bash
cd EDA_FLIGHT
```

---

## Install Dependencies

```bash
pip install pandas numpy scikit-learn openpyxl jupyter
```

---

## Run Notebook

```bash
jupyter notebook
```

Open

```
Flight_EDA.ipynb
```

---

# 📚 Required Libraries

```python
import pandas as pd
import numpy as np
from sklearn.preprocessing import OneHotEncoder
```

---

# 📈 Workflow

```
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Missing Value Handling
      │
      ▼
Feature Engineering
      │
      ▼
Categorical Encoding
      │
      ▼
Machine Learning Ready Dataset
```

---

# 💡 Key Learning Outcomes

- Data Cleaning
- Feature Engineering
- Datetime Feature Extraction
- Handling Missing Values
- One-Hot Encoding
- Data Preprocessing
- Preparing Real-World Data for Machine Learning

---

# 🚀 Future Improvements

- Exploratory Data Visualization
- Correlation Analysis
- Outlier Detection
- Feature Scaling
- Machine Learning Models
- Hyperparameter Tuning
- Model Evaluation
- Streamlit Deployment

---

# 👨‍💻 Author

## **Fuzail Khan**

**CSE Graduate**

### Skills

- Python
- SQL
- Data Analysis
- Machine Learning
- Pandas
- NumPy
- Scikit-Learn
- Data Visualization

**GitHub:** https://github.com/Fuzail93

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

# ⭐ Show Your Support

If you found this project useful, please give it a ⭐ on GitHub.

Your support helps improve the project and encourages future development.

---

# 📜 License

This project is developed for educational and learning purposes.
