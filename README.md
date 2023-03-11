# Music-Genre-Classification-with-Machine-Learning-in-Python-and-Visualization-in-Tableau

Part 1: Importing the Dataset and getting familiar with it.

In this project, I used 2 data files: fma-rock-vs-hiphop.csv, echonest-metrics.json. I first familiarized myself with the code. Then, I merged the 2 datasets together and filtered only desired columns. 

Part 2: Exploratory Data Analysis

I performed Exploratory Data Analysis (EDA) using Tableau. Check out my Dashboard.
https://public.tableau.com/app/profile/sakshi.sanjay.sharma/viz/ExploringAudioGenresandFeatures/Dashboard1

Part 3: Preprocessing the Data for Modeling

I implemented Prinicpal Component Analysis to reduce the dimensonality of the dataset. I used the explained_variance_ratio_ attribute to obtain an array of values that represents the proportion of the total variance in the original dataset that is explained by each principal component. I used bar chart to visualize the explained variance ratio of each principal component. The plot allowed me to visualize the contribution of each principal component in explaining the variance in the dataset. From the plot I observed that 6 features can explain 85% of the variance. Hence, I used 6 components to perform PCA.

Part 4: Machine Learning Models

After analyzing the data, I implemented machine learning models, including Decision Tree, Logistic Regression, and Random Forest Classifier, to classify songs into two genres, Hip-Hop and Rock. I evaluated the performance of these models using metrics such as precision, recall, F1-score, and accuracy, and found that the Random Forest Classifier performed the best with an F1 score of 90

Based on the classification reports, we can see that the Random Forest Classifier model performed the best, with an accuracy of 0.90 and higher precision, recall, and F1-score for both classes compared to the other models. The Logistic Regression model also performed well, with an accuracy of 0.88 and high precision, recall, and F1-score for the Rock class, but lower scores for the Hip-Hop class. The Decision Tree model had the lowest accuracy of the three models at 0.85, with lower precision, recall, and F1-score for both classes compared to the other models.

Overall, the results suggest that the Random Forest Classifier model is the most effective at classifying the songs into their respective genres based on the given features. 

The goal of this project was to develop a music genre classification model using machine learning techniques and to visualize the data using Tableau. Through the analysis and modeling, I was able to develop an understanding of the characteristics that distinguish Hip-Hop and Rock genres and build a model that can classify songs with a high degree of accuracy.
