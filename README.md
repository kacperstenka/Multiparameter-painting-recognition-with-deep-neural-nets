# Multiparameter painting recognition with deep neural nets

My MSc Thesis, in which I have implemented a multi-layered system for painting classification in 4 categories: 
  * style, 
  * genre, 
  * artist 
  * century of creation. 

I have used four convolutional neural networks (CNNs) to classify a painting between various classes within each of these categories, then gathered all of the predictions and used another layer of classifiers - carried out experiments with:
* SVMs, 
* RLs, 
* RFs, 
* MLPs 
* 1/2/3-layered neural nets

to make a 2nd level prediction based on CNNs predictions for every class. 
It was proved, that for some categories using a two-level approach may significantly increase the accuracy of classification - especialy for the painting style and the century of creation identification.

## Technologies

To complete this project I have used:
* Python 3.9
* Jupyter Notebook
* Scikit-Learn
* Numpy
* Pandas
* Matplotlib
* Plotly
* Tensorflow
* Keras
* Cuda w/ CuDNN
* Tqdm
* io
* os
* Joblib

## Database

As data to train my system, I have used the WikiArt.com dataset containing over 80,000 paintings. It is available to download under the link: https://archive.org/details/wikiart-dataset

## Other info

#### Whole process of designing, training and evaluation of this system (as well of how neural nets work and much more) had been described in Polish in file Praca_Magisterska.pdf. 
#### Code samples are available in the so named subfolder, with comments (also in Polish).

MSc Thesis was written for the Department of Electronics of Wroclaw Univeristy of Science and Technology, under supervision of PhD Piotr Ciskowski.
