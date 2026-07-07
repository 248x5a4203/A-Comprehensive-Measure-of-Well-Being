# A-Comprehensive-Measure-of-Well-Being
# 🌍 A Comprehensive Measure of Well-Being (HDI Prediction System)

## 📖 Overview

**A Comprehensive Measure of Well-Being** is a Machine Learning web application that predicts the **Human Development Index (HDI)** of a country using key socio-economic indicators. The project leverages a **Linear Regression** model trained on historical Human Development Index data and deploys it through a **Flask** web application.

The Human Development Index (HDI) is a composite measure developed by the United Nations to evaluate a country's overall development by considering three major dimensions:

- 🩺 Health (Life Expectancy)
- 🎓 Education (Expected and Mean Years of Schooling)
- 💰 Standard of Living (Gross National Income per Capita)

Unlike traditional economic measures such as GDP, HDI provides a broader perspective on a country's quality of life and human well-being.

---

# 🎯 Objectives

- Predict the Human Development Index (HDI) score.
- Analyze relationships between socio-economic indicators and HDI.
- Build a Linear Regression machine learning model.
- Deploy the trained model using Flask.
- Provide an interactive web interface for real-time HDI prediction.

---

# 🚀 Features

- Human Development Index prediction
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Correlation heatmap visualization
- Linear Regression model
- Model evaluation using R² Score
- Model serialization using Pickle
- Flask web application
- Interactive prediction interface
- User-friendly frontend

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Pandas | Data Processing |
| NumPy | Numerical Computing |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-learn | Machine Learning |
| Pickle | Model Serialization |
| Flask | Web Framework |
| HTML5 | Frontend Development |
| CSS3 | Styling |
| Visual Studio Code | Development Environment |

---

# 📂 Project Structure

```text
HDI-Prediction-System/
│
├── Dataset/
│   └── hdi_dataset.csv
│
├── Model/
│   └── hdi_model.pkl
│
├── Static/
│   ├── css/
│   ├── images/
│   └── js/
│
├── Templates/
│   ├── home.html
│   ├── indexnew.html
│   └── result.html
│
├── app.py
├── model.py
├── requirements.txt
├── README.md
└── Documentation.md
```

---

# ⚙️ Machine Learning Workflow

## Epic 1 – Environment Setup

- Installed required Python libraries
- Configured project folder structure

---

## Epic 2 – Import Required Libraries

Imported:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Pickle
- Flask

---

## Epic 3 – Dataset Download and Understanding

- Downloaded HDI dataset
- Loaded dataset using Pandas
- Explored dataset structure
- Performed statistical analysis
- Created visualizations
- Generated correlation heatmap

---

## Epic 4 – Data Preprocessing

- Selected independent variables (X)
- Selected dependent variable (Y)
- Checked missing values
- Filled null values using mean imputation

---

## Epic 5 – Train-Test Split

- Divided dataset into:
  - Training Data (80%)
  - Testing Data (20%)

---

## Epic 6 – Model Building

- Trained Linear Regression model
- Generated predictions
- Compared actual and predicted values
- Evaluated using R² Score

---

## Epic 7 – Model Saving

- Serialized model using Pickle
- Saved as `hdi_model.pkl`

---

## Epic 8 – Flask Web Application

- Built Flask backend
- Created Home page
- Developed Prediction page
- Loaded trained model
- Generated HDI predictions
- Displayed prediction results

---

# 📊 Dataset Information

| Property | Value |
|----------|-------|
| Dataset | Human Development Index |
| Source | GitHub Guided Projects |
| Records | 195 Countries |
| Features | 82 Columns |
| Target Variable | HDI Score |

---

# 📈 Model Used

**Algorithm**

Linear Regression

**Input Features**

- Country
- Life Expectancy
- Expected Years of Schooling
- Mean Years of Schooling
- Gross National Income (GNI) per Capita

**Output**

- Human Development Index (HDI) Score

---

# 🌐 Application Workflow

```text
User Opens Website
        │
        ▼
Home Page
        │
        ▼
Prediction Page
        │
        ▼
Enter Country Details
        │
        ▼
Submit Form
        │
        ▼
Flask Backend
        │
        ▼
Load Pickle Model
        │
        ▼
Linear Regression Prediction
        │
        ▼
Display HDI Score
```

---

# ▶️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/hdi-prediction-system.git
```

Navigate to the project directory

```bash
cd hdi-prediction-system
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
python app.py
```

Open your browser

```text
http://127.0.0.1:5000/
```

---

# 📷 Screenshots

### Home Page

Displays project introduction and navigation to prediction page.

### Prediction Page

Allows users to enter country development indicators.

### Prediction Result

Displays the predicted Human Development Index (HDI) score.

---

# 📌 Future Enhancements

- Add multiple regression models for comparison.
- Improve prediction accuracy through feature engineering.
- Deploy the application on cloud platforms such as IBM Cloud or Render.
- Add interactive dashboards and charts.
- Integrate real-time global HDI datasets.
- Implement user authentication and prediction history.

---

# 🎯 Outcome

The project successfully demonstrates the complete machine learning lifecycle, from data collection and preprocessing to model development, evaluation, deployment, and real-time prediction using a Flask web application.

Users can easily input socio-economic indicators and receive an estimated Human Development Index (HDI) score, making the system useful for educational purposes, policy analysis, and development research.

---

# 👨‍💻 Author

**SmartBridge SkillWallet AI/ML Internship Project**

**Project Title:** A Comprehensive Measure of Well-Being (HDI Prediction System)

Developed as part of the SmartBridge AI & Machine Learning Internship Program.
