# Machine-learning-tutorial --Individual assignment

**SVM Classifier on Iris Dataset
==============================**

This project demonstrates how to use Support Vector Machines (SVM) with different kernel functions (linear, polynomial, and RBF) to classify the famous Iris dataset. It also visualizes the decision boundaries for each SVM model using sepal length and sepal width as features.

**Dataset
-------**
The Iris dataset is a classic multivariate dataset introduced by Ronald Fisher. It contains 150 samples of iris flowers, each described by four features:
- Sepal length
- Sepal width
- Petal length
- Petal width
This project only uses the first two features (sepal length and width) for visualization purposes.

**Technologies Used
-----------------**
- Python 3
- NumPy
- Matplotlib
- scikit-learn

**How It Works
------------**
1. Load the Dataset:
   The Iris dataset is loaded using sklearn.datasets.
2. Feature Selection:
   Only the first two features (sepal length and width) are selected for 2D visualization.
3. Train/Test Split:
   The dataset is split into training and testing sets using train_test_split.
4. Model Training:
   Three SVM classifiers are trained using different kernel types:
   - Linear
   - Polynomial (poly)
   - Radial Basis Function (rbf)
5. Evaluation:
   Accuracy for each model is calculated on the test data.
6. Visualization:
   Decision boundaries for each SVM model are plotted using matplotlib.

**Output
------**
The script will display 3 plots, one for each kernel type, showing the decision boundaries and the accuracy of each model.

**Usage
-----**
Prerequisites:
Make sure you have the following Python packages installed:
pip install numpy matplotlib scikit-learn

**Run the Script:**
python svm_iris.py
(Replace 'svm_iris.py' with the filename you saved the script as.)

**Author
------**
This project was built as a demonstration of SVMs in scikit-learn with basic visualization.
Feel free to use and modify this project for learning or educational purposes.
