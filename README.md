# 🎬 Movie Rating Prediction using Machine Learning

## 📌 Project Overview

Movie ratings play a crucial role in helping audiences discover quality content. This project focuses on building a **Machine Learning Regression Model** that predicts movie ratings based on various attributes such as **genre, release year, duration, votes, director, and cast information**.

The project follows a complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and performance evaluation.

---

## 🎯 Objectives

* Predict movie ratings using machine learning regression techniques.
* Perform data cleaning and preprocessing on the IMDb movie dataset.
* Explore relationships between movie features and ratings.
* Build and evaluate a regression model capable of estimating movie ratings.
* Gain insights into the factors influencing movie ratings.

---

## 📂 Dataset

The project uses the **IMDb Movies India Dataset**, which contains information about movies, including:

* Movie Name
* Year of Release
* Genre
* Duration
* Director
* Actor 1
* Actor 2
* Actor 3
* Number of Votes
* IMDb Rating

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 📊 Project Workflow

### 1. Data Collection

* Loaded the IMDb movie dataset.

### 2. Data Preprocessing

* Removed duplicate records.
* Handled missing values.
* Cleaned the **Year**, **Duration**, and **Votes** columns.
* Selected relevant features for model training.

### 3. Exploratory Data Analysis (EDA)

* Analyzed feature distributions.
* Explored relationships between movie attributes and ratings.
* Visualized important trends using charts and graphs.

### 4. Feature Engineering

* Processed categorical variables.
* Encoded movie genres.
* Prepared numerical features for machine learning.

### 5. Model Building

A **Random Forest Regressor** was used to predict movie ratings because it effectively captures nonlinear relationships and provides strong predictive performance.

### 6. Model Evaluation

The model was evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## 📈 Results

The Random Forest Regression model demonstrated effective performance in estimating movie ratings by learning patterns from movie metadata and user engagement features.

The project showcases the complete regression modeling pipeline, from preprocessing and feature engineering to evaluation and prediction.

---

## 📷 Visualizations

The project includes several visualizations, including:

* Rating Distribution
* Genre Distribution
* Movie Release Year Distribution
* Correlation Heatmap
* Votes vs Rating
* Duration vs Rating
* Actual vs Predicted Ratings

---

## 🚀 How to Run the Project

### Clone the repository

```bash
git clone https://github.com/your-username/movie-rating-prediction.git
```

### Navigate to the project directory

```bash
cd movie-rating-prediction
```

### Install the required libraries

```bash
pip install -r requirements.txt
```

### Run the Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook and execute the cells sequentially.

---

## 📁 Project Structure

```text
Movie-Rating-Prediction/
│
├── IMDb Movies India.csv
├── Movie_Rating_Prediction.ipynb
├── README.md
├── requirements.txt
└── images/
    ├── rating_distribution.png
    ├── correlation_heatmap.png
    └── actual_vs_predicted.png
```

---

## 🔮 Future Improvements

* Compare multiple regression algorithms.
* Apply Hyperparameter Tuning.
* Perform advanced feature engineering.
* Use Target Encoding for high-cardinality categorical features.
* Deploy the model using Streamlit or Flask.
* Build an interactive movie rating prediction web application.

---

## 📚 Machine Learning Concepts Used

* Regression
* Exploratory Data Analysis (EDA)
* Data Cleaning
* Feature Engineering
* Data Preprocessing
* Model Evaluation
* Random Forest Regression

👩‍💻 Author

Aayushi Yadav

Aspiring Data Scientist passionate about Machine Learning, Data Analytics, and Artificial Intelligence.

GitHub: https://github.com/Aayushi72
LinkedIn: (https://www.linkedin.com/in/aayushi-yadav-30635a2a7)

⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub. It helps support my work and encourages me to build more data science projects.


