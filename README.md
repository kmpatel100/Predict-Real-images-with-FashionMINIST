# Predict-Real-images-with-FashionMINIST
In this Repository, I generated models that can predict real images that are trained on the computer-generated image of fashion items. I also create embeddings to visualize data in 3-dimensions with PCA and T-SNE. 

## Model with Prediction
In this file, I preprocessed data and generate a convolutional neural network with a saving model.
In the section of Import_Resize_Reshape_prediction, I did all the transformation of images without saving images as a file without image generator function so, everyone can understand how the whole process works of image transformation.
In the end, I predicted 30 images that I downloaded from the internet.

## Generate_Visualization
In this file, I generated embeddings from the test dataset. by embeddings, we can use tensroboard to see data in 3-dimensions with help of PCA(Principal component analysis) and T-SNE(t-distributed stochastic neighbor embedding) which help us to understand how data works in multi-dimension. with T-SNE we can also understand which fashion items have similar features that define how our model can predict the wrong prediction between two fashion items.

### Principal component analysis 
![Alt Text](https://github.com/kmpatel100/Predict-Real-images-with-FashionMINIST/blob/master/Media/PCA.gif)

### t-distributed stochastic neighbor embedding
![Alt Text](https://github.com/kmpatel100/Predict-Real-images-with-FashionMINIST/blob/master/Media/T-SNE.gif)
