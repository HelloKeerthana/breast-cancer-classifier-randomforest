<h1>Breast Cancer Prediction using Random Forest Classifier</h1>

<h2>Dataset</h2>
<p>The dataset used is the Breast Cancer dataset from <strong>sklearn.datasets</strong>. 
  It includes various features related to breast cancer cells and is typically used for classification tasks to predict whether a tumor is malignant or benign.</p>

<h2>Modules Used</h2>
<ul>
    <li><strong>sklearn.datasets</strong>: To load the Breast Cancer dataset.</li>
    <li><strong>sklearn.model_selection</strong>: For splitting the dataset into training and testing sets using <code>train_test_split</code>.</li>
    <li><strong>sklearn.ensemble</strong>: For creating and training the Random Forest Classifier using <code>RandomForestClassifier</code>.</li>
    <li><strong>sklearn.metrics</strong>: For evaluating the model performance, especially the accuracy score.</li>
</ul>

<h2>Process</h2>
<p>The dataset is loaded and split into training and test sets using <strong>train_test_split</strong>.
  A Random Forest Classifier is then trained using the training set. Finally, predictions are made on the test set and the results are plotted for comparison.</p>

<h2>Output</h2>
<p>The output consists of a scatter plot displaying true vs predicted labels for the training set, with different colors representing the true and predicted values.</p>
