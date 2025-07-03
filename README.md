## 🎶 Recording Listener Profiles -- Analyzing Music and Mental Health
This project explores the intricate relationship between music preferences and mental health indicators like anxiety, depression, and insomnia. By applying statistical techniques such as clustering, we identify distinct listener profiles revealing the correlation of different musical genres with mental health and overall well-being.

## 📊 Overview

* **Objective**: To investigate the relationship between music preferences and associated mental health conditions
* **Key Questions**:
    1.  How do different genres of music impact mental health?
    2.  Can clustering reveal hidden patterns in music preferences and mental health metrics?
* **Dataset**: Self-reported survey data on genres, musical preferences, and mental health metrics [Kaggle Dataset](https://www.kaggle.com/datasets/catherinerasgaitis/mxmh-survey-results)
* **Tools**: R (for statistical modeling and visualization)

## 💡 Project Highlights

1.  **Data Preprocessing**:
    * Identified and handled missing values
    * Filtered BPM values in the range 20-220 for consistency
2.  **Exploratory Data Analysis (EDA) and Visualization**:
    * Structured and encoded variables into a cohesive dataframe
    * Visualized correlations using **hierarchical** cluster correlation plots
3.  **K-Means Clustering Techniques**:
    * Determined optimal clusters using Elbow Method
    * Validated clustering using Silhouette Method
4.  **Cluster Visualizations**:
    * Generated a heatmap for cluster variable means
    * Created parallel coordinates plot to analyze cluster characteristics
5.  **Interpretations**:
    * Identified distinct listener profiles based on their music preferences and mental health metrics
    * Observed lower levels of anxiety and depression for soft music preferences (e.g. classical, jazz), and slightly elevated levels for hard music preferences (e.g. rock, metal)
