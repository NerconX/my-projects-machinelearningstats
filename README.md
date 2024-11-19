<h1> Statistical and Machine Learning Projects </h1>
multiple projects done in school with machine learning

<!DOCTYPE html>
<html>
<body>
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
<h1>Project 1 - Multiphase Flow Pattern Classification using K-Nearest Neighbors</h1>

<p>This project implements a k-Nearest Neighbors (k-NN) classifier to analyze and classify multiphase flow patterns using the <code>BD12Experiments6FP.csv</code> dataset. The analysis includes parameter optimization and performance evaluation.</p>

<h2>Overview</h2>
<p>The code performs the following main tasks:</p>

<h3>1. Data Loading and Preprocessing:</h3>
<ul>
 <li>Loads the <code>BD12Experiments6FP.csv</code> dataset</li>
 <li>Separates features and target variables</li>
 <li>Splits data into training (80%) and testing (20%) sets</li>
 <li>Applies standard scaling to normalize the features</li>
</ul>

<h3>2. Initial KNN Classification:</h3>
<ul>
 <li>Implements basic k-NN classifier</li>
 <li>Evaluates initial performance metrics</li>
 <li>Generates confusion matrix visualization</li>
</ul>

<h3>3. Parameter Optimization:</h3>
<ul>
 <li>Uses <code>GridSearchCV</code> to find optimal k value</li>
 <li>Tests k values from 1 to 50</li>
 <li>Implements cross-validation</li>
 <li>Applies best parameters to improve model performance</li>
</ul>

<h3>4. Performance Comparison:</h3>
<ul>
 <li>Compares accuracy before and after optimization</li>
 <li>Visualizes results using bar charts</li>
 <li>Analyzes confusion matrices</li>
 <li>Reports precision, recall, and F1 scores</li>
</ul>

<h2>Results</h2>
<p>The optimization process improved the model's performance:</p>
<ul>
 <li>Initial accuracy: 87%</li>
 <li>Optimized accuracy: 90%</li>
 <li>Overall improvement: 3%</li>
</ul>
<p>The optimized model showed better precision and F1 scores across all classes, indicating more reliable predictions.</p>

<h2>Requirements</h2>
<ul>
 <li>Python 3.x</li>
 <li>Required libraries:
   <ul>
     <li>numpy</li>
     <li>pandas</li>
     <li>scikit-learn</li>
     <li>matplotlib</li>
     <li>seaborn</li>
   </ul>
 </li>
</ul>

<h2>Usage</h2>
<ol>
 <li>Ensure all required libraries are installed</li>
 <li>Place the <code>BD12Experiments6FP.csv</code> file in the same directory as the notebook</li>
 <li>Run the Jupyter notebook cells sequentially</li>
 <li>View results and visualizations</li>
</ol>

<h2>Files</h2>
<ul>
 <li><code>hw1GM.ipynb</code>: Main Jupyter notebook containing all code and analysis</li>
 <li><code>BD12Experiments6FP.csv</code>: Dataset containing multiphase flow pattern data</li>
</ul>

<h2>Implementation Details</h2>
<p>The implementation follows these steps:</p>
<ol>
 <li>Data splitting: 80-20 train-test split</li>
 <li>Feature scaling using StandardScaler</li>
 <li>Initial k-NN implementation with default parameters</li>
 <li>Grid search for optimal k value</li>
 <li>Performance evaluation using multiple metrics</li>
 <li>Visualization of results using confusion matrices and bar charts</li>
</ol>
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
<body>
<h1>Project 2 - Breast Cancer Classification using Logistic Regression</h1>
<p>This project implements a Logistic Regression classifier to analyze and classify breast cancer tumors as benign or malignant using the Breast Cancer Wisconsin dataset. The analysis includes parameter optimization and performance evaluation.</p>

<h2>Overview</h2>
<p>The code performs the following main tasks:</p>

<h3>1. Data Loading and Preprocessing:</h3>
<ul>
 <li>Loads the Breast Cancer Wisconsin dataset</li>
 <li>Separates features and target variables</li>
 <li>Splits data into training and testing sets</li>
 <li>Applies standard scaling to normalize the features</li>
</ul>

<h3>2. Initial Logistic Regression:</h3>
<ul>
 <li>Implements basic logistic regression classifier</li>
 <li>Evaluates initial performance metrics</li>
 <li>Generates confusion matrix visualization</li>
 <li>Calculates precision, recall, and F1 scores</li>
</ul>

<h3>3. Parameter Optimization:</h3>
<ul>
 <li>Uses GridSearchCV for hyperparameter tuning</li>
 <li>Tests different values for regularization parameter C</li>
 <li>Evaluates different penalty types (l1, l2)</li>
 <li>Implements cross-validation</li>
</ul>

<h3>4. Performance Comparison:</h3>
<ul>
 <li>Compares accuracy before and after optimization</li>
 <li>Analyzes confusion matrices</li>
 <li>Visualizes results using bar charts</li>
 <li>Reports detailed classification metrics</li>
</ul>

<h2>Results</h2>
<p>The optimization process showed minimal impact on model performance:</p>
<ul>
 <li>Initial accuracy: 97%</li>
 <li>Optimized accuracy: 96%</li>
 <li>Slight decrease in accuracy: -1%</li>
</ul>
<p>The high initial accuracy suggests the base model was already well-optimized for this classification task.</p>

<h2>Requirements</h2>
<ul>
 <li>Python 3.x</li>
 <li>Required libraries:
   <ul>
     <li>numpy</li>
     <li>pandas</li>
     <li>scikit-learn</li>
     <li>matplotlib</li>
     <li>seaborn</li>
   </ul>
 </li>
</ul>

<h2>Usage</h2>
<ol>
 <li>Ensure all required libraries are installed</li>
 <li>Load <code>Project2.ipynb</code> in Jupyter Notebook/Lab</li>
 <li>Run all cells sequentially</li>
 <li>Review results and visualizations</li>
</ol>

<h2>Files</h2>
<ul>
 <li><code>Project2.ipynb</code>: Main Jupyter notebook containing all code and analysis</li>
 <li>Uses built-in sklearn breast cancer dataset</li>
</ul>

<h2>Implementation Details</h2>
<p>The implementation follows these steps:</p>
<ol>
 <li>Dataset loading and feature extraction</li>
 <li>Train-test data splitting</li>
 <li>Feature standardization</li>
 <li>Initial logistic regression model implementation</li>
 <li>Grid search for optimal parameters</li>
 <li>Comprehensive performance evaluation</li>
 <li>Results visualization through confusion matrices</li>
</ol>

<h2>Key Findings</h2>
<ul>
 <li>The initial model achieved high accuracy (97%)</li>
 <li>Parameter optimization did not significantly improve performance</li>
 <li>Both models showed strong classification capabilities for benign and malignant tumors</li>
 <li>The optimized model found best performance with L1 penalty and C=1</li>
</ul>

<h2>Acknowledgments</h2>
<ul>
 <li>Breast Cancer Wisconsin Dataset contributors</li>
</ul>

<h1>Project 3 - Breast Cancer Classification using Hierarchical and K-Means Clustering</h1>
<p>This project implements both hierarchical and k-means clustering algorithms to analyze and classify breast cancer data using the Breast Cancer Wisconsin dataset. The analysis includes multiple linkage criteria for hierarchical clustering and parameter optimization for k-means clustering.</p>

<h2>Overview</h2>
<p>The code performs the following main tasks:</p>

<h3>1. Data Loading and Preprocessing:</h3>
<ul>
 <li>Loads the Breast Cancer Wisconsin dataset from sklearn</li>
 <li>Separates features and target variables</li>
 <li>Applies standard scaling to normalize the features</li>
 <li>Prepares data for both clustering approaches</li>
</ul>

<h3>2. Hierarchical Clustering Analysis:</h3>
<ul>
 <li>Implements clustering with multiple linkage criteria:
   <ul>
     <li>Ward linkage</li>
     <li>Complete linkage</li>
     <li>Average linkage</li>
     <li>Single linkage</li>
   </ul>
 </li>
 <li>Generates dendrograms for visual analysis</li>
 <li>Compares clustering structures across different methods</li>
</ul>

<h3>3. K-Means Clustering Analysis:</h3>
<ul>
 <li>Implements k-means clustering with optimization</li>
 <li>Evaluates performance using multiple metrics:
   <ul>
     <li>Inertia (Elbow method)</li>
     <li>Silhouette score</li>
     <li>Calinski-Harabasz score</li>
   </ul>
 </li>
 <li>Visualizes clustering results using PCA</li>
</ul>

<h3>4. Performance Evaluation:</h3>
<ul>
 <li>Compares clustering results with actual labels</li>
 <li>Generates confusion matrices</li>
 <li>Analyzes cluster quality metrics</li>
 <li>Provides visual representations of results</li>
</ul>

<h2>Results</h2>
<p>The analysis provides insights into the natural groupings within the breast cancer data:</p>
<ul>
 <li>Hierarchical clustering reveals the hierarchical structure of the data</li>
 <li>K-means clustering achieves optimal performance with k=2 clusters</li>
 <li>Results align well with the binary nature of the diagnosis (malignant/benign)</li>
</ul>

<h2>Requirements</h2>
<ul>
 <li>Python 3.x</li>
 <li>Required libraries:
   <ul>
     <li>numpy</li>
     <li>pandas</li>
     <li>scikit-learn</li>
     <li>matplotlib</li>
     <li>seaborn</li>
     <li>scipy</li>
   </ul>
 </li>
</ul>

<h2>Usage</h2>
<ol>
 <li>Ensure all required libraries are installed</li>
 <li>Run the Python script or Jupyter notebook</li>
 <li>View the generated visualizations and analysis results</li>
 <li>Check the summary metrics printed at the end of execution</li>
</ol>

<h2>Files</h2>
<ul>
 
 <li><code>Project2.ipynb</code>: Main Python script containing all code and analysis</li>
 <li>Dataset: Built-in Breast Cancer Wisconsin dataset from sklearn</li>
</ul>

<h2>Implementation Details</h2>
<p>The implementation follows these steps:</p>
<ol>
 <li>Data preprocessing with StandardScaler</li>
 <li>Hierarchical clustering implementation with four linkage methods</li>
 <li>K-means clustering with parameter optimization</li>
 <li>Performance evaluation using multiple metrics</li>
 <li>Visualization of results using:
   <ul>
     <li>Dendrograms</li>
     <li>PCA plots</li>
     <li>Confusion matrices</li>
     <li>Evaluation metric plots</li>
   </ul>
 </li>
</ol>
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

</body>
</html>
