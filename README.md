# Star-Type-KNN-Prediction-Model
<b>Tech Tools Required :</b>
<ul>
  <li>Jupyter Notebook</li>
  <li>Scikit Learn KNN Classifier Model</li>
  <li>Pandas</li>
  <li>Numpy</li>
  <li>Matplotlib</li>
</ul>
<p>The prediction model utlizes the <b>KNeighborsClassifier of sklearn module </b>which is a KNN Model to train</p>
<p> Since there was not much data so 50% was used for training while 50% was used for testing purpose</p>
<p>After Scaling down the data using <b> sklearn.StandardScaler </b> cross validation is performed to find out the optimal neighbour count</p>
<img src = "https://github.com/Aksgo/Star-Type-KNN-Prediction-Model/blob/main/neighbour_accuracy.png?raw=true" width="400px" heigh="250px">
<p>Fitting the model using best neighbour count achieved : <b>We got an accuracy of 98.9% on test data</b>
<p><i>Here is the Scatter plot <b>Actual Values vs Predicted Values</b> on Complete Dataset of which shows that model has correctly classfied the data</i></p>
<img src="https://github.com/Aksgo/Star-Type-KNN-Prediction-Model/blob/main/comparison_subplots.png?raw=true">

<hr>
<h3>NOTE : The Data is acquired from kaggle <br><br> You may check out here : https://www.kaggle.com/datasets/deepu1109/star-dataset/data </h3>
