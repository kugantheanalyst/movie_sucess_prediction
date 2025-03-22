# 🎬 Movie Success Prediction

## 📖 Project Overview
This project aims to predict a movie’s success based on various attributes such as budget, cast popularity, genre, and more. Using machine learning techniques, we classify movies into three categories: **Hit**, **Average**, and **Flop**, based on their IMDB scores.

## 🚀 Features
- **Data Exploration & Visualization**: Understanding the dataset with various insights.
- **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature selection.
- **Machine Learning Model**: Implementing a **Random Forest Classifier** for prediction.
- **Performance Evaluation**: Analyzing model accuracy using classification metrics.
- **Dashboard (Optional)**: An interactive Power BI dashboard for visualizing insights.

## 🛠️ Tech Stack
- **Programming Language**: Python
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
- **Visualization**: Power BI (for an interactive dashboard)

## 📦 Dataset
The dataset contains **28 variables** for **5043 movies** spanning 100 years and 66 countries. Key features include:
- **movie_title**: Title of the movie
- **duration**: Movie length in minutes
- **director_name**: Name of the director
- **genres**: Categories such as Action, Comedy, Sci-Fi, etc.
- **budget**: Movie budget in USD
- **imdb_score**: IMDB rating (target variable)

## 🛠️ Installation
Ensure you have Python installed. Install dependencies using:

```bash
# Clone the repository
git clone https://github.com/kugantheanalyst/movie-success-prediction.git
cd movie-success-prediction

# Install required Python packages
pip install -r requirements.txt
