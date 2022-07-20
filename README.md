# Melanoma Detection
> Here buisness requrement to build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- We have image dataset which is imbalanced where melanoma have maximum number of image and seborrhic have min
- Using RGB image for training model to clasify the image.

## Conclusions
- In experiment 1 I have created a model with 32, 64 filter oc conv with kernel size 3 and then passed to dense to classes. In this experiment achived approx 55% accuracy on train and valiation set but when tested on test set then only  35% accuracy which seems that model is under fited.
- In experiment 2 i.e. with agumentation and increasing conv layer and epoch able to achive 79.5% accuracy on train and 69.5 % on test which seem model little bit overfitted



## Technologies Used
- matplotlib - 3.3.1
- seaborn - 0.11.0
- numpy - 1.22.2
- pandas - 1.1.4
- tensorflow

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@shubham-sri](https://github.com/shubham-sri) - feel free to contact me!


## License
This project is open source and available under the [... License](./LICENSE).