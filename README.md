# 9 Tomato Disease Detection & Classification (94 % accuracy )
<img src="https://www.saferbrand.com/media/articles/images/790/sb_us_t_main_Tomato_problems_2015-07-14.jpg" alt="tomato" width="900" height="500">
<p>Tomato is an inseparable part of India's diet, that's why in the fiscal year 2020, the volume of tomato production in India amounted to over 21 million metric tons. But this number can be even pushed further if tomato fields are get protected by malicious diseases which results in severe losses for farmers both in terms of money and time.  In order to fight this problem, I have created a deep learning model that is capable of identifying healthy tomatoes plant and 9 most harmful and popular diseases of tomatoes that are bacterial spot, early blight, late blight, leaf mold, septoria leaf spot, spider mites, target spot, yellow leaf curl virus, and tomato mosaic virus. 
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
<h2>Introduction</h2>
<p>I have created a deep learning model that is efficiently able to identify nine tomato diseases. The model uses conventional layers at the core for feature extraction and use dense layers for the classification task. The dataset used for model training was downloaded from Kaggle (https://bit.ly/3qOrdX0).</p>
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
<p>The model consists of four convolutional layers for feature extraction from the images, each followed by a max-pooling layer and having the same padding. After the convolutional and max-pooling layers, the model uses two dense layers for the classification task. All the layers use the Relu activation function except the last dense layer, which uses the softmax activation function. The model was trained for 10 epochs with batch size equals to 574. During the training process parse categorical cross-entropy loss function was used along with Adam optimizer.</p>
<h2>Model Evaluation</h2>
  
<img src="https://github.com/NavinBondade/10-Tomato-Disease-Detection-and-Classification-/blob/main/Tomato%20Disease%20and%20Classification/Graphs%20and%20Pictures/Loss.png" width="450" height="300">
<p>After training the model has shown loss: 0.1904 and accuracy: 0.9400 for training data and loss: 0.1604 and accuracy: 0.9461 for validation data (this clearly shows that model trained perfectly without overfitting or underfitting)</p>

<h2>Licensing</h2>  
Copyright [2021] [Navin Bondade]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
