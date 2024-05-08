# iris-flower-classificatoin
Summary of the Solution:

In order to categorize iris flowers into the appropriate species (setosa, versicolor, and virginica) based on their measurements, a machine learning model must be trained. Features including sepal length, sepal breadth, petal length, and petal width are measured. We have been informed that iris flower classification data can be found in the Scikit-learn library and can be utilized for this purpose.


The code that is provided describes how to use machine learning techniques to categorize iris blossoms into the appropriate species. Here's a summary of the actions needed:

1.Importing required libraries: For data manipulation, machine learning, and data visualization, the code imports necessary libraries like Pandas, Scikit-learn, and Matplotlib.

2.Get the dataset loaded: A CSV file is used to load the Iris dataset.

3.Preprocessing of the Dataset: The 'Id' column is removed from the dataset because it is not necessary for the analysis. The dataset is then divided into labels (y) and features (X).

4.Model Development and Instruction:

K-Nearest Neighbors (KNN) Model: Using the training set of data, a KNN classifier with one neighbor is built.
Decision Tree Model: Using the training data, a Decision Tree classifier is built and trained.

5.Evaluation of the Models: Using both training and test datasets, the accuracy of the KNN and Decision Tree models is assessed. In this step, the models' classification accuracy of the iris blossoms is evaluated.

6.New Predictions: Using iris measurements, the trained models are applied to new input samples to generate predictions.


7.Data Visualization: To illustrate the correlations between features, data visualization is carried out using pairplots. A bar chart that contrasts the models' test and training accuracies further sheds light on how well they function.

8.Conclusion: Both KNN and Decision Tree models were trained and assessed, according to the code comments, which provide an overview of the findings. It draws attention to the successful forecasts and attained accuracy for fresh input data. Additionally, it emphasizes how crucial data visualization is to evaluating model success.

In conclusion, the method provides a thorough way to categorize different species of iris using machine learning methods. It offers important insights into model performance and dataset features by covering data preprocessing, model training, evaluation, and visualization.

