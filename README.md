
README for CSC869 Term Project: Movie Recommendation System

Project Overview:
----------------
This project is focused on developing a movie recommendation system. Utilizing various data processing and machine learning techniques, the system aims to provide users with movie recommendations based on their preferences and viewing history.

Programming Language and Environment
- Language: Python
- Environment: Jupyter Notebook

Dependencies and Installation:
-----------------------------
For developing and running this project, you can use one of the following Python IDEs (PyCharm,Visual Studio Code (VS Code),Jupyter Notebook etc..)

To run this project, the following Python libraries are required. Install them using pip:
pip install pandas
pip install numpy
pip install scikit-learn
pip install matplotlib
pip install seaborn
pip install jupyter
pip install swifter
pip install nltk
pip install wheel
pip install scikit-surprise


Existing Software and Toolkits:
------------------------------
Pandas and NumPy: These are used to organize and handle the movie data. They help in sorting, filtering, and preparing the data for analysis, which is crucial in understanding user preferences and movie characteristics.

Scikit-learn: This library is used for converting movie descriptions into numerical form using TF-IDF Vectorization and then calculating similarities between movies with cosine similarity, aiding in the recommendation of similar movies to users.

Matplotlib and Seaborn: These tools are used for creating charts and graphs. They help in visually representing the data, making it easier to understand patterns and insights about movie preferences and trends.

Jupyter Notebook: It's the platform where all the code is written and run. It's like a digital notebook that combines code, visualizations, and text in one place, making it easier to see the results of the code and make changes as needed.

Swifter: This tool helps in making data processing faster. When working with large movie datasets, it speeds up the calculations, saving time and making the system more efficient.

NLTK (Natural Language Toolkit): This is used for analyzing the text related to movies, like descriptions or reviews. It helps in breaking down and understanding the text, which is important for recommending movies based on their content.

Surprise: Utilized for its SVD (Singular Value Decomposition) model, this toolkit helps to predict user ratings for movies, enabling the system to recommend films that align with individual user preferences.


Data Sources:
------------
The project uses publicly available movie datasets. Follow these steps to download and read the datasets:
1. Download the dataset from https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset/data
2. Place the downloaded files in a directory accessible to the Jupyter Notebook.
3. Use the provided Python scripts in the notebook to read and process the datasets.

Running the Program:
-------------------
1. Open the Jupyter Notebook in your development environment.
2. Ensure all dependencies are installed.
3. Run the cells in the notebook sequentially to execute the program.
PS : don't forget to update working directory ( where the data files have been downloaded)

Integration of Toolkits with Custom Code:
----------------------------------------
The project integrates external toolkits with custom Python code to achieve functionalities like data preprocessing, feature extraction, and model training for the recommendation system.
