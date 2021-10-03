# Identifying Nine Tomato Disease With Deep Learning
<p align="center">
<a href="https://nbviewer.jupyter.org/github/NavinBondade/Identifying-Nine-Tomato-Disease-With-Deep-Learning/blob/main/Tomato%20Disease%20and%20Classification/NoteBook/10_Tomato_Disease_Detection_and_Classification_with_94_accuracy_.ipynb" target="_blank">
  <img align="center"  src="https://github.com/NavinBondade/Distinguishing-Fake-And-Real-News-With-Deep-Learning/blob/main/Graphs/button_if-github-fails-to-load-the-notebook-click-here%20(4).png?raw=true"/>
</a>
</p>

<p align="center">
<a href="https://nitnetomatodiseases.herokuapp.com"  target = "_blank">
  <img align="center"  src="https://github.com/NavinBondade/Identifying-Nine-Tomato-Disease-With-Deep-Learning/blob/main/Tomato%20Disease%20and%20Classification/Graphs%20and%20Pictures/webappbtn.png" height="50" />
</a>
</p>

<p align="center">
<a onclick="window.open ('http://www.foracure.org.au', ''); return false" href="javascript:void(0);">
  <img align="center"  src="https://github.com/NavinBondade/Identifying-Nine-Tomato-Disease-With-Deep-Learning/blob/main/Tomato%20Disease%20and%20Classification/Graphs%20and%20Pictures/webappbtn.png" height="50" />
</a>
</p>



<img src="https://www.saferbrand.com/media/articles/images/790/sb_us_t_main_Tomato_problems_2015-07-14.jpg" alt="tomato" width="900" height="500">
<p>Tomato is an inseparable part of India's diet, that's why in the fiscal year 2020, the volume of tomato production in India amounted to over 21 million metric tons. But this number can be even pushed further if tomato fields are get protected by malicious diseases which results in severe losses for farmers both in terms of money and time. To fight this problem, I have created a deep learning model that is capable of identifying healthy tomatoes plant and 9 most harmful and popular diseases of tomatoes that are bacterial spot, early blight, late blight, leaf mold, septoria leaf spot, spider mites, target spot, yellow leaf curl virus, and tomato mosaic virus. 
</p>
<h2>Libraries Used</h2>
<ul>
  <li>Tensorflow</li>
  <li>Keras</li>
  <li>Numpy</li>
  <li>Pandas </li>
  <li>Matplotlib</li>
  <li>Numpy</li>
  <li>Glob</li>
</ul> 
<h2>Data Visualization</h2>
<ul>
  <li><h3>Healthy</h3></li>
</ul>  
<img src="https://github.com/NavinBondade/10-Tomato-Disease-Detection-and-Classification-/blob/main/Tomato%20Disease%20and%20Classification/images/Healthy.png" width="450" height="450">
<ul>
  <li><h3>Nine Diseases</h3></li>
</ul>  
<img src="https://github.com/NavinBondade/10-Tomato-Disease-Detection-and-Classification-/blob/main/Tomato%20Disease%20and%20Classification/images/Nine%20Tomato%20Disease.png" alt="tomato diseases" width="700" height="700">
<h2>Model Details</h2>
<p>The model consists of four convolutional layers for feature extraction from the images, each followed by a max-pooling layer and having the same padding. After the convolutional and max-pooling layers, the model uses two dense layers for the classification task. All the layers use the Relu activation function except the last dense layer, which uses the softmax activation function. The model was trained for 10 epochs with batch size equals to 574. During the training process sparse categorical cross-entropy loss function was used along with Adam optimizer.</p>
<h2>Model Evaluation</h2>
<img src="https://github.com/NavinBondade/10-Tomato-Disease-Detection-and-Classification-/blob/main/Tomato%20Disease%20and%20Classification/Graphs%20and%20Pictures/Loss.png" width="450" height="300">
<p>After training the model has shown loss: 0.1904 and accuracy: 0.9400 for training data and loss: 0.1604 and accuracy: 0.9461 for validation data (this clearly shows that model trained perfectly without overfitting or underfitting)</p>
<h2>Conclusion</h2>  
<p>In this project, I have created a deep convolutional neural network architecture that correctly identifies the nine harmful tomato diseases with an accuracy of 94 percent.</p>
