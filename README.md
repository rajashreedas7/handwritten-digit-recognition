# Supervised Learning for Limited Feature Hand Written Digit Recognition

The following steps were performed while making this project:

1. Data was collected manually using cellphone camera and then various examples were seperated into folders with the name of their classes
2. The collected examples were masked and resized.
3. The masked images were put into an empty folder class-wise.
4. Now, the folder was downloaded and seperated into 15 training and 5 test examples and again put into folders class-wise, manually.
5. The train and test examples were converted into grayscale and was flattened to transform into an 1D numpy array.
6. The following classification algorithms were used to predict the results :
    * Support Vector Machine Classifier
    * Random Forest Classifier
    * Extra Trees Classifier
    * Gaussian Naive Bayes Classifier 
7. It was observed that Random Forest Classifier could predict with *94%*, Support Vector Machine Classifier with *92%*, Extra Trees Classifier with *84%* and Gaussian Naive Bayes Classifier with *80%* accuracy, respectively.

##### Therefore, we could see that even with only 20 dataset per class, our model could perform quite well.

Packages and libraries used:
* sklearn
* numpy
* cv2
* matplotlib
* os
* PIL
