# Decision-Tree-Classifier

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: YASH MANAV

*INTERN ID*: CT06WP88

*DOMAIN*: MACHINE LEARNING

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTOSH

###**Building and Visualizing a Decision Tree Model Using Scikit-Learn**

In this project, I built and visualized a Decision Tree model using the Scikit-Learn library to classify and predict outcomes based on the well-known Iris dataset. Below is a step-by-step breakdown of how I completed the task.

### **Step 1: Importing the Necessary Libraries**
To begin, I imported the required libraries from Scikit-Learn:
- `load_iris` to load the Iris dataset.
- `train_test_split` to split the dataset into training and testing sets.
- `DecisionTreeClassifier` to create and train the decision tree model.
- `accuracy_score` to evaluate the performance of the model.

### **Step 2: Loading the Dataset**
Next, I loaded the Iris dataset using `load_iris()`. The dataset consists of four features (sepal length, sepal width, petal length, and petal width) and three target classes representing different species of the Iris flower.

Here, `X` contains the feature matrix (the input variables), and `y` contains the target labels (the species of the iris flowers).

### **Step 3: Splitting the Dataset**
To train and evaluate the model, I split the dataset into a training set (70%) and a test set (30%) using `train_test_split()`.

This ensures that 70% of the data is used to train the model, while the remaining 30% is used to test its performance. The `random_state=99` ensures reproducibility.

### **Step 4: Initializing and Training the Decision Tree Classifier**
I initialized the Decision Tree model using `DecisionTreeClassifier()`, specifying a `random_state` to maintain consistency across runs.

Then, I trained the classifier using the training data:

The `fit()` function enables the model to learn the patterns in the training data and build a decision tree.

### **Step 5: Making Predictions**
Once the model was trained, I used it to make predictions on the test set:

This generates an array of predicted class labels for the test set.

### **Step 6: Evaluating Model Performance**
To assess the accuracy of the model, I compared the predicted values (`y_pred`) with the actual values (`y_test`) using `accuracy_score()`:

The accuracy metric provides an indication of how well the model performed in classifying the Iris flowers.

### **Step 7: Visualizing the Decision Tree**
A crucial part of this project was to visualize the trained decision tree. To achieve this, I used the `plot_tree` function from Scikit-Learn:

### **Results and Observations**

The final accuracy score indicated how well the model performed on the test set. Given that the Iris dataset is relatively simple and well-structured, the Decision Tree classifier performed quite well.

By visualizing the decision tree, I was able to interpret how the model made decisions based on feature values. Each split in the tree represents a decision rule that helps classify a data point into one of the three species categories.

###OUTPUT

![Image](https://github.com/user-attachments/assets/f48e87e5-c607-4f6b-bba9-fabb8a6619e0)
