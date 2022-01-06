# Classification-of-Pneumonia-from-Chest-X-rays
* CNN Model for classifying Pneumonia in chest X Rays
* CNN Model
3 Conv2D layer (filter=32, kernel_size=(3,3), activation=”relu”) </br>
MaxPool2D layer ( pool_size=(2,2))
3 Conv2D layer (filter=64 , kernel_size=(3,3), activation=”relu”)
Flatten layer to squeeze the layers into 1 dimension
Dense Fully connected layer ( activation=”relu”)
Dense layer (activation=”softmax”)
Visualized in confusion matrix
Dataset from  Kaggle.
total number of observations (images): 5,856
