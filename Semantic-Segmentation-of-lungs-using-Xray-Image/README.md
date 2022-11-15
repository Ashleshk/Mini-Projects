# Semantic Segmentation of the lungs from X-ray images
* [kaggle project](https://www.kaggle.com/code/ashleshkhajbage/semantic-segmentation-of-lungs-using-xray-image?scriptVersionId=111025682)


* A model of the segmentation of the lung region from the x-ray images, the model relies on forming a mask through which that region can be cut.

* The methodology that was followed to build the model, depends on the use of a pre-trained model, to extract the characteristics from it, and then rely on those characteristics and train them to find a mathematical formula that links these characteristics to each other and thus the ability to build the mask as required. The following images show the characteristics of one of the X-ray images, which were extracted from the previously trained VGG19 model, where the layer to be extracted from the features was selected.

* In the next stage, all the images will be passed to the previous model to get the attributes for each attribute, from which the required dataset is formed.

* The methodology is based on that the sum of the attributes of each pixel corresponds to the value of the pixel in the mask image, and therefore each pixel of the mask image (TARGET) corresponds to 64 attributes of the corresponding pixel value of the X-ray image.

## Result

* The following diagrams show the results obtained for the training data and the test data.
download (75) download (76)
![training](https://github.com/Ashleshk/Mini-Projects/blob/main/Semantic-Segmentation-of-lungs-using-Xray-Image/images/training.png)![loss ratio](https://github.com/Ashleshk/Mini-Projects/blob/main/Semantic-Segmentation-of-lungs-using-Xray-Image/images/validation.png)

* The model has been tested on a number of images:

![result](https://github.com/Ashleshk/Mini-Projects/blob/main/Semantic-Segmentation-of-lungs-using-Xray-Image/images/result.png)