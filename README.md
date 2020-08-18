# Decision-Tree-Classification-on-Diabetes-Dataset
It shows how to build and optimize Decision Tree Classifier of "Diabetes dataset" using Python Scikit-learn package.
A decision tree is a flowchart-like tree structure where an internal node represents feature(or attribute), the branch represents a decision rule, and each leaf node represents the outcome. The topmost node in a decision tree is known as the root node. It learns to partition on the basis of the attribute value. It partitions the tree in recursively manner call recursive partitioning. This flowchart-like structure helps you in decision making. It's visualization like a flowchart diagram which easily mimics the human level thinking. That is why decision trees are easy to understand and interpret.

1.  Importing Required Libraries
Let's first load the required libraries.

2.Loading Data
Let's first load the required Diabetes dataset using pandas read CSV function. You can download the data here (datasets_set.csv)

3. Feature Selection
Here, you need to divide given columns into two types of variables dependent(or target variable) and independent variable(or feature variables).

4. Splitting Data
To understand model performance, dividing the dataset into a training set and a test set is a good strategy.

Let's split the dataset by using function train_test_split(). You need to pass 3 parameters features, target, and test_set size.

5. Building Decision Tree Model
Let's create a Decision Tree Model using Scikit-learn.

6. Evaluating Model
Let's estimate, how accurately the classifier or model can predict the type of cultivars.

Accuracy can be computed by comparing actual test set values and predicted values.

7.Visualizing Decision Trees
