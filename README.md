# Lung-Disease-Using-Deep-Learning

Through this project we want to help medical sector. Through this project we aim to make to patient self dependent to predict he/she is having `PNEUMONIA` or not. We uses the Deep Learning concept which is `CONVOLUTION NEURAL NETWORK` and we also uses the concept of `Transfer Learning(Pretrained Model)`.

In the starting we loaded the Dataset from the kaggle website and do the data cleaning and data Augmentation and after that we just created the Architecture of the Deep Neural Network and fits the train dataset to the NEURAL NETWORK.

And in the end we just passes the image of the `X-Ray` to the model and then it just predict that particular `X-Ray` is having PNEUMONIA or not.

## Modules used:
* keras
    * layers
        * Input
        * Lambda
        * Dense
        * Flatten
    * models
        * Model
    * applications
        * VGG16
        * preprocess_input
    * preprocessing
        * image
        * ImageDataGenerator
* numpy
* glob
* matplotlib

## To check a person is having PNEUMONIA or not
run a following command in command prompt
```
jupyter notebook(in the main directory)
```
## Deployment
```
1. Data Extraction
2. Exploratory Data Analysis(EDA)
3. Feature Engineering
4. Image Generator
5. Data Augmentation
6. Construct the Architecture of the Neural Network
7. Tuning the model
8. Building Flask API
9. Pushing code to Github
```


## Demo

![App Screenshot](https://raw.githubusercontent.com/Franky-Saxena/Lung-Disease-Using-Deep-Learning/main/Untitled2.png)
![App Screenshot](https://raw.githubusercontent.com/Franky-Saxena/Lung-Disease-Using-Deep-Learning/main/Untitled1.png)
