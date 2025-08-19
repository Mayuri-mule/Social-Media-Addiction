Social Media Clustering & Prediction


This project explores the relationship between students' social media usage patterns and various life outcomes, including academic performance, mental health, and personal relationships. By applying clustering techniques and predictive modeling, we aim to uncover patterns in social media behavior and assess their potential impact on students' well-being.



📊 Dataset

The analysis uses the Students' Social Media & Relationships dataset, which contains anonymized survey responses from students across multiple countries and academic levels. Key dimensions include:

Usage intensity – average daily hours spent on social media

Platform preferences – favored social media platforms

Addiction score – level of social media dependency

Mental health score – self-reported mental health

Impact on academics – whether social media affects academic performance

Relationship dynamics – quality of personal and social relationships

Each row represents one student’s response, providing a cross-sectional snapshot suitable for statistical analysis and machine learning applications.




🔍 Objectives

Identify behavioral patterns in social media usage among students.

Cluster students into distinct groups based on usage and behavioral features.

Predict academic impact using supervised machine learning models.

Visualize key insights to help educators and policymakers understand trends.



🧪 Tools & Libraries

Python

Data manipulation: pandas, numpy

Data visualization: matplotlib, seaborn

Machine learning: scikit-learn

Jupyter Notebook for interactive analysis



🛠 Methodology

Data Cleaning & Preprocessing

Handle missing values, normalize categorical variables, and encode target labels.

Exploratory Data Analysis (EDA)

Study distributions, detect outliers, and analyze correlations between features.



Clustering

Apply K-Means clustering to group students based on social media usage and behavioral features.

Determine optimal cluster numbers using the Elbow Method.


Predictive Modeling

Build logistic regression models to predict if social media usage affects academic performance.

Evaluate model performance using confusion matrix, classification report, and ROC curves.



Visualization

Visualize clusters, correlations, and model performance for better interpretation.



📈 Key Findings (Sample)

Students with higher social media addiction scores tend to report lower mental health scores.

Clustering reveals distinct groups such as high-usage high-impact vs moderate-usage low-impact students.

Logistic regression indicates daily usage hours and addiction score are significant predictors of academic impact.



🔮 Future Work / Extensions

Include temporal data to track usage trends over time.

Explore deep learning models for more accurate prediction.

Integrate survey responses on well-being and productivity for richer insights.

Use other clustering algorithms like DBSCAN or hierarchical clustering for comparison.
