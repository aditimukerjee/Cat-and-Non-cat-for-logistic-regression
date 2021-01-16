Using a Logistic regression along with Neural Networks for Cat vs Non-Cat Image Classification
We will be covering up the concepts of using the logistic regression along with neural networks, 
applying forward and backward propagation, and then applying them to the practice in order to build your image recognition system 
i.e a cat classifier in this case. This cat classifier takes an image as an input and then it predicts whether the image contains a cat or 
not with 70% accuracy and the tools used will be Jupyter Notebook and the code is written in python.

Logistic Regression
Logistic regression is the appropriate regression analysis to conduct when the dependent variable is dichotomous (binary). 
Like all regression analyses, the logistic regression is a predictive analysis.

How do computers interpret Images

For a computer, an image is just an array of values. Typically it's a 3-dimensional (RGB) matrix of pixel values.
Where each pixel has a specific value of red, green, and blue that represents the color of a given pixel. 
Neural networks process images using matrixes of weights called filters (features) that detect specific attributes such as vertical edges, horizontal edges, etc.
Moreover, as the image progresses through each layer, the filters are able to recognize more complex attributes.

DATASET
The dataset is saved here:https://github.com/aditimukerjee/Cat-and-Non-cat-for-logistic-regression

Each image is of shape (num_px, num_px, 3) where 3 is for the 3 channels (RGB) and num_px is the height equal to the width of a training image. Thus, each image is square (height = num_px) and (width = num_px).

CONCLUSION
The accuracy of the training set is 99.99% and the accuracy of the testing set is 72%. Out of the six images used for prediction, one image was predicted incorrectly since the accuracy is still low and it can be further improved.
