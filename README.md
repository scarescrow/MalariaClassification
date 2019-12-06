# Malaria Detection in Blood Cells

Cell detection and classification on images of blood cells to detect presence of cells infected with malaria

### Data

We used the [Malaria Bounding Boxes](https://www.kaggle.com/kmader/malaria-bounding-boxes) dataset to train our model.

### Models

We used bounding boxes to extract the cells from the images. Using these, we trained 4 CNN-based classification models to predict whether the cell is infected or not. The models we used are:

* AlexNet
* MobileNet
* ResNet
* Xception

Additionally, image augmentation techniques were also used to improve the performance of the models. All the code to process the data is present in the [code](code/) directory