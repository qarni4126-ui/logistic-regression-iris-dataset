🌸 Logistic Regression on the Iris Dataset
📘 Project Overview

This project applies Logistic Regression, a supervised machine learning algorithm, to the classic Iris dataset to classify flower species based on their sepal and petal measurements. It demonstrates the complete machine learning workflow — from data exploration to model evaluation.

🎯 Objectives

Perform Exploratory Data Analysis (EDA) to understand feature distributions and relationships.

Train a Logistic Regression model to classify Iris flowers into three species: setosa, versicolor, and virginica.

Evaluate the model using accuracy, confusion matrix, and classification metrics.

📊 Key Steps

Load Dataset: Used sns.load_dataset("iris") from Seaborn or sklearn.datasets.load_iris.

EDA: Visualized feature relationships using pairplots, histograms, and boxplots.

Preprocessing: Encoded target labels and split data into training and testing sets.

Model Building: Trained a multinomial Logistic Regression model.

Evaluation: Assessed model performance with accuracy and confusion matrix visualization.

📈 Results

Achieved an accuracy of ~96–98% on the test data.

Model performed best in separating Setosa and Virginica species.

Logistic Regression effectively captured linear relationships among features.

🧠 Insights

Petal length and petal width are the most influential features for classification.

Even with a simple linear model, strong predictive performance is achieved on this well-structured dataset.

🛠️ Technologies Used

Python, Pandas, NumPy

Seaborn, Matplotlib (for EDA)

Scikit-learn (for model building and evaluation)

🏁 Conclusion

This project showcases the power of Logistic Regression in solving a classic multiclass classification problem. It highlights the importance of EDA and demonstrates how even simple algorithms can perform exceptionally well with clean, well-defined data.
