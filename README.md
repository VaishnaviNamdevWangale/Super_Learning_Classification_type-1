1.Import Required Libraries
    Imported essential libraries such as:
    pandas, numpy for data handling.
    matplotlib.pyplot, seaborn for visualization.
    sklearn.model_selection for splitting the dataset.
    sklearn.tree for building a decision tree model.
    sklearn.metrics for evaluating performance.

2.Load the Dataset
    Used pd.read_csv() to load the dataset.
    Displayed the first few rows using .head().

3.Explore the Dataset
    Checked:
    Shape of the data.
    Column names and data types.
    Null values using .isnull().sum().
    Statistical summary using .describe().

4.Visualize the Data
    Created bar plots, count plots, and other charts using seaborn and matplotlib to understand class distribution and feature relevance.

5.Data Preprocessing
    Handled missing values (if any).
    Converted categorical variables to numerical using encoding (LabelEncoder or OneHotEncoder).
    Selected input features (X) and target label (y).

6.Train-Test Split
    Divided the dataset into training and test sets using train_test_split().

7.Train the Decision Tree Classifier
    Created a Decision Tree model using DecisionTreeClassifier().
    Fit the model on training data.

8.Model Prediction & Evaluation
    Predicted using model.predict().
    Evaluated the model using:
    Confusion Matrix
    Accuracy Score
    Classification Report

9.Visualize the Tree (Optional)

Used plot_tree() to visualize the structure of the decision tree.

