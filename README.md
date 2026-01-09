# 📊Udemy Recommendation System

## 🧾 Overview
This project is a content-based recommendation system designed to suggest relevant Udemy courses to users. It uses cosine similarity to measure the similarity between courses based on their features and recommends the most relevant courses accordingly. The goal is to demonstrate practical application of data preprocessing and similarity-based machine learning techniques in Python.

## 📂 Dataset
The project uses a Udemy courses dataset containing information such as:
- **Course title**
- **Course instructor**
- **Description**
- **Rating**
- **User_vote**
- **Total_hours**
- **Lecture**
- **Level**

The dataset is loaded and processed to extract meaningful features for similarity calculation.

## 🛠️ Tools & Technologies
- **Python** – Core programming language  
- **Pandas** – Data loading and preprocessing  
- **Scikit-learn** – Feature extraction and cosine similarity

## ⚙️ Project Steps
1. Load and explore the Udemy dataset
2. Clean and preprocess relevant features
3. Convert textual data into numerical vectors
4. Apply cosine similarity to compute similarity between courses
5. Generate course recommendations based on similarity scores

## 📈 Results
- The system successfully recommends courses that are closely related to a given course or user preference.
- Recommendations are ranked based on cosine similarity scores, ensuring relevance and consistency.

## ▶️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/udemy-recommendation-system.git
```
2. Navigate to the project directory:
```bash
cd udemy-recommendation-system
```
3. Install required libraries:
```bash
pip install pandas scikit-learn
```
4. Run the Python script or Jupyter Notebook to generate recommendations.
