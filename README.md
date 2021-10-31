# Sign Language Recognition Using OpenCV

## Dependencies:

* ### Tensorflow
* ### Keras
* ### OpenCV
  

### Basically, our [dataset](https://www.kaggle.com/datamunge/sign-language-mnist) (from kaggle) consists of many images of 24 (except J and Z) American Sign Language alphabets. Each image has size 28×28 pixel which means total 784 pixels per image.

![Image](https://github.com/Kratos-is-here/Sign-Language-Recognition/blob/main/IMAGES/sign_language_letters.png)


### We use CNNs (Convolutional Neural Networks) to recognise the alphabets.

![model summary](https://github.com/Kratos-is-here/Sign-Language-Recognition/blob/main/IMAGES/model_summary.png)

### Our model’s accuracy is 94% so it should recognise alphabets without any problem with plain background and descent lights.