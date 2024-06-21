# Star-Type-KNN-Prediction-Model
<b>Tech Tools Required :</b>
<ul>
  <li>Jupyter Notebook</li>
  <li>Scikit Learn KNN Classifier Model</li>
  <li>Pandas</li>
  <li>Numpy</li>
  <li>Matplotlib</li>
</ul>
<p>The prediction model utlizes the <b>KNeighborsClassifier of sklearn module </b>which is a KNN Model to train the data</p>
<p>After Scaling down the data using <b> sklearn.StandardScaler </b> cross validation is performed to find out the optimal neighbour count</p>
<img src = "https://github.com/Aksgo/Star-Type-KNN-Prediction-Model/blob/main/neighbour_accuracy.png?raw=true" width="400px" heigh="250px">
<p>Fitting the model using best neighbour count achieved : <b>We got an accuracy of 98.9% on test data</b>
<p><i>Here is the Scatter plot of Actual Values (blue circle) and Predicted Values (black square) of Star Type vs spectral value</i></p>


<hr>
<h3>NOTE : The Data is acquired from kaggle <br><br> You may check out here : https://www.kaggle.com/datasets/deepu1109/star-dataset/data </h3>
