<!DOCTYPE html>
<html>
<body>

<h1>Machine-Learning-SVM-Cancer-Cell-Classification</h1>

<h2>Purpose</h2>

<p>The purpose of this project is to classify whether a human cell sample is benign (non-cancerous) or malignant (cancerous), based on the physical characteristics of the cells. The analysis will be done using the Support Vector Machine (SVM) algorithm, a supervised machine learning model.</p>

<h2>Impact</h2>

<p>The impact of this project is the potential application of this model in healthcare and medical diagnosis, by assisting doctors in diagnosing cancerous cell samples based on their physical characteristics. This can aid in early detection of cancer, leading to more effective treatment and a higher survival rate.</p>

<h2>Description</h2>

<p>The SVM algorithm works by mapping data to a high-dimensional feature space, and then finding a hyperplane within this feature space that separates the classes of data. Once the hyperplane is found, new data can be mapped onto the same space and predicted to belong to a class based on which side of the plane they fall on.</p>

<p>In this project, the SVM model is built and trained on a dataset of human cell sample records. Each record contains the values of a set of cell characteristics, as well as a diagnosis of whether the cell is benign or malignant, as confirmed by separate medical procedures.</p>

<p>The model is then tested on unseen data, and its performance is evaluated using various metrics, such as the confusion matrix, F1 score, and Jaccard index.</p>

<h2>Workflow</h2>

<ol>
  <li>Data Loading: The dataset is publicly available from the UCI Machine Learning Repository and contains several hundred human cell sample records. The data is loaded into a Pandas DataFrame.</li>
  <li>Data Preprocessing: The data is checked for any inconsistencies, such as non-numerical values, and these are addressed as necessary. The dataset is then split into a training set and a test set.</li>
  <li>Model Training: The SVM model is trained on the training set using the sklearn library. The radial basis function (RBF) kernel is used.</li>
  <li>Model Testing: The model is used to predict the classes of the test set.</li>
  <li>Evaluation: The performance of the model is evaluated using the confusion matrix, F1 score, and Jaccard index.</li>
</ol>

<h2>Results</h2>

<p>The trained SVM model is able to classify cell samples with a high level of accuracy, indicating that it could potentially be a useful tool in medical diagnosis. Below are the calculated performance metrics:</p>

<ul>


  <li>F1 Score: 0.9639038982104676</li>
  <li>Jaccard Index: 0.9444444444444444</li>
</ul>

<h2>Conclusion</h2>

<p>This project demonstrated the application of the SVM algorithm in classifying cancer cells. The high performance of the model on the test data suggests that SVM is a suitable model for this type of classification task, and could potentially be applied in a real-world healthcare setting.</p>

<h2>Benefits to the User</h2>

<p>Users can leverage the power of machine learning to assist in medical diagnoses, potentially leading to earlier detection of cancer. By applying this model to cell sample data, doctors and healthcare professionals can gain valuable insights and make more accurate diagnoses.</p>

</body>
</html>
