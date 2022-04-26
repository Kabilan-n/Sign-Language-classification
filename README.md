# Sign-Language-classification
Along with result comparison for multiple CNN models

## Dataset Description:

Dataset taken from [ardamavi Github Repo](https://github.com/ardamavi/Sign-Language-Digits-Dataset) . Created by  Ankara Ayrancı Anadolu High School Students. 

Kaggle link for this dataset: [link](https://www.kaggle.com/code/kabilan03/sign-language-classification)


Dataset contains images of ign language representation of numbers from 0 to 9 (10 classes) . Each image of size 100 x 100 pixels. 

## Data split

  * Train       85%
  * Validation  7.5%
  * Test        7.5%

The classification process was done with four different pre-defined models ( **XceptionNet**, **MobileNet**, **VGG16**, **InceptionNet** ) transfered learned with imageNet weights, loss function used is categorical cross entropy and the optimizer is Adam optimizer with learning rate 0.0001

## Performance comparision of different models

| Model  | Accuracy |
| ------------- | ------------- |
| XceptionNet  | 97%  |
| MobileNet  | 84%  |
| VGG16  | 98%  |
| InceptionNet  | 93%  |
