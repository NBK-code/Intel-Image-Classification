# Intel Image Classification
Image Images Dataset available from [Kaggle](https://www.kaggle.com/datasets/puneet6060/intel-image-classification) contains over 25,000 images of size 150x150 distributed under 6 categories. The categories are as follows:

1. Buildings
2. Forest
3. Glacier
4. Mountain
5. Sea
6. Street

Some of the images in the dataset are displayed below.

![alt text](https://github.com/NBK-code/Intel-Image-Classification/blob/main/Illustrative_Images/Intel_Images.png?raw=true)


Three transfer learning models were built using 

1. VGG16
2. Inception v3 
3. ResNet50. 

VGG16 provided a better accuracy of 88% on the test set (containing 3000 images) with just a few epochs of training. The confusion matrix for the VGG16 model on the test set is given below.

![alt text](https://github.com/NBK-code/Intel-Image-Classification/blob/main/Illustrative_Images/VGG16_confusion_matrix.png?raw=true)
