# Classification-of-Pneumonia-from-Chest-X-rays
* CNN Model for classifying Pneumonia in chest X Rays
* CNN Model
3 Conv2D layer (filter=32, kernel_size=(3,3), activation=”relu”) </br>
MaxPool2D layer ( pool_size=(2,2)) </br>
3 Conv2D layer (filter=64 , kernel_size=(3,3), activation=”relu”) </br>
Flatten layer to squeeze the layers into 1 dimension </br>
Dense Fully connected layer ( activation=”relu”) </br>
Dense layer (activation=”softmax”) </br>
Visualized in confusion matrix </br>
Dataset from  Kaggle. </br>
total number of observations (images): 5,856
