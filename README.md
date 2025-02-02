# Song-Popularity-and-Genre-Prediction
This project explores Spotify's music dataset to uncover insights about song characteristics, genres, and popularity. It involves data preprocessing, visualization, feature engineering, and machine learning models for predicting song popularity (regression) and classifying genres (classification).
Project Objectives

Data Cleaning & Preprocessing:

        Handling missing values.
        Dropping irrelevant columns (artist_name, track_id, track_name).
        Removing duplicate records.
        Standardizing numerical features using StandardScaler.
        One-hot encoding categorical columns.

Exploratory Data Analysis (EDA):
    
        Statistical Summary: Understanding the distribution of features.
        Correlation Matrix: Identifying relationships between numerical variables.
        Genre Distribution: Understanding music genre diversity.
        Violin Plots: Visualizing feature distributions.
        Popularity Trends by Genre: Analyzing the variation of song popularity.

Regression Models (Predicting Popularity):
        
        Decision Tree Regressor (with GridSearchCV for hyperparameter tuning).
        Random Forest Regressor.
        Gradient Boosting Regressor.
        Performance Metrics: Root Mean Squared Error (RMSE), R² Score.
            
Classification Models (Predicting Genre):

        Logistic Regression.
        K-Nearest Neighbors (KNN).
        Support Vector Machine (SVM).
        Performance Metrics: Accuracy, Classification Report.

Visualizations & Insights:

        Violin Plots: Help in understanding feature distributions (e.g., loudness, energy, and tempo).
        Heatmap (Correlation Matrix): Identifies relationships between popularity, danceability, loudness, etc.
        Genre Distribution: Shows the frequency of tracks per genre.
        Popularity Analysis: Helps in identifying which genres tend to have higher popularity.

Tools & Technologies Used:

        Python: Data processing, visualization, and modeling.
        Pandas & NumPy: Data manipulation.
        Matplotlib & Seaborn: Data visualization.
        Scikit-Learn: Machine learning models.
        Jupyter Notebook: Interactive analysis.

Conclusion:

        This project provides actionable insights into music trends and applies machine learning to predict song popularity and classify genres. The findings can guide music recommendations, playlist generation, and            marketing strategies for streaming platforms.
