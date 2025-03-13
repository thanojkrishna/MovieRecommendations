# Movie Recommendation System

## 🎬 Project Overview
This project focuses on developing a movie recommendation system that leverages data processing and machine learning techniques to provide users with personalized movie suggestions based on their preferences and viewing history.

## 📁 Repository Structure

### 📂 data/
Contains datasets used for analysis and modeling.
- `movies_metadata.csv`: Metadata of movies including titles, genres, and descriptions.
- `ratings.csv`: User ratings for various movies.

### 📂 notebooks/
Jupyter notebooks detailing data analysis, preprocessing, and model development.
- `Movie_Recommendation_System.ipynb`: Main notebook encompassing data preprocessing, exploratory data analysis (EDA), and model implementation.

### 📂 scripts/
Python scripts for data processing and model functions.
- `data_preprocessing.py`: Script for cleaning and preparing the dataset.
- `model_training.py`: Script for training and evaluating recommendation models.

### 📂 reports/
Documentation and reports generated from the analysis.
- `Final_Report.pdf`: Detailed report summarizing methodologies, findings, and conclusions.

### 📄 requirements.txt
Lists the Python packages required to run the project.

## 🔍 Exploratory Data Analysis (EDA)
- **Movie Popularity**: Analysis of the most rated and highest-rated movies.
- **User Behavior**: Insights into user rating patterns and preferences.
- **Genre Trends**: Examination of popular genres over time.

## 🧠 Modeling Approach
Implemented recommendation algorithms:
1. **Content-Based Filtering**: Recommends movies similar to those a user has liked, based on movie features like genres and descriptions.
2. **Collaborative Filtering**: Suggests movies based on user behavior and preferences, identifying patterns among users with similar tastes.
3. **Hybrid Approach**: Combines both content-based and collaborative filtering to enhance recommendation accuracy.

### Evaluation Metrics
Models were evaluated using:
- **Precision**: Proportion of recommended movies that are relevant.
- **Recall**: Proportion of relevant movies that are recommended.
- **F1-Score**: Harmonic mean of precision and recall.

*Detailed performance metrics are available in the final report.*

## 🚀 How to Use This Repository

1. **Clone the Repository**:
```bash
git clone https://github.com/thanojkrishna/MovieRecommendations.git
cd MovieRecommendations
```

2. **Set Up the Environment**:
- Ensure you have Python installed (preferably version 3.7 or higher).
- Install necessary packages:
```bash
pip install -r requirements.txt
```

3. **Explore the Data**:
- Access the `notebooks/` directory to view and run Jupyter notebooks.
- Open `Movie_Recommendation_System.ipynb` to follow the analysis and modeling steps.


## 🙏 Acknowledgements
- Data sourced from [TMDB Dataset](https://www.kaggle.com/tmdb/tmdb-movie-metadata).
- Special thanks to the course instructors for guidance and support.

---
Feel free to fork, star, or contribute to this repository if you find it useful!
