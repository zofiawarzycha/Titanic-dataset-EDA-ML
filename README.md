# Project Overview
This project is a comprehensive introduction to Machine Learning, combining theoretical foundations with a practical implementation using the famous Titanic dataset. The primary goal is to predict passenger survival based on various features such as age, class, and socio-economic status. The repository includes detailed study notes on ML metrics and a hands-on assignment focused on building and optimizing classification models.

# Part 1 – Data Analysis & Preprocessing
Objectives:

Exploratory Data Analysis (EDA): Understand the distribution of passenger data and identify correlations between features (e.g., how passenger class or gender influenced survival rates).

Feature Selection: Identify key predictors for the model, specifically focusing on Pclass, Sex, and engineered features.

Feature Engineering: Enhance the dataset by creating new informative columns, such as IsAlone, to capture social dynamics that impacted survival.

Data Transformation: Encode categorical variables (like gender) into numerical formats suitable for machine learning algorithms.

Data Scaling: Apply StandardScaler to normalize numerical features, ensuring compatibility and better performance for distance-based models like K-Nearest Neighbors (KNN).

Train-Test Split: Implement a robust validation strategy by splitting the data into training (80%) and testing (20%) sets using a fixed random_state for reproducibility.

# Part 2 – Machine Learning Models
Objectives:

Baseline Establishment: Use a DummyClassifier to set a performance floor, providing a point of comparison for more complex models.

Model Implementation: Develop and compare multiple supervised learning algorithms:

Decision Tree Classifier: An intuitive model used to understand decision boundaries.

K-Nearest Neighbors (KNN): A proximity-based classifier used to identify patterns among similar passengers.

Hyperparameter Tuning: Systematically investigate model parameters to maximize performance:

For Decision Trees: Tune max_depth and splitting criteria (Gini vs. Entropy) to prevent overfitting.

For KNN: Optimize the number of neighbors (k) and distance metrics to achieve the best accuracy.

Performance Evaluation: Analyze model success using a comprehensive suite of metrics:

Accuracy: Overall correctness of the model.

Precision & Recall: Specifically evaluating the model's ability to correctly identify survivors without excessive false positives.

F1-Score: The harmonic mean of precision and recall for a balanced view of model quality.

Visual Interpretation: Utilize Confusion Matrices to visualize true positives versus false negatives, providing deep insight into where the model succeeds and where it fails.
