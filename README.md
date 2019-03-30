# Cat_vs_dog_keras_binary_classification

Cat vs Dog binary classification implemented in a tensorflow's high level Api Keras.

Basic requirements:

```javascript
tensorflow 
keras 
Pillow
numpy 
pandas
matlpotlib
```

To install above mentioned requirements to your system first set-up pip installer for your python then run following commands in cmd:

```javascript
pip install tensorflow
pip install tensorflow-gpu
pip install pillow
pip install numpy
pip install pandas
pip install matplotlib
```
Tensorflow gpu for those who have cuda enabled gpu on thier system.

To directly test this project go to downloaded directory and run Cat_vs_Dog_predict.ipynb in jupyter-notebook or jupyter lab.

This python notebook load pretrained model and predict your given image .Any value less than 0.5 means Cat and above 0.5 means Dog.

To train your own model first go to this link and download cats and dogs dataset:

(https://www.microsoft.com/en-us/download/confirmation.aspx?id=54765)

To make numpy array from images use Pillow library which allow us to resize image and also allow us to make black and white image from rgb image. (Black&White images are easy to train and computably less heavy on your machine)

I use my created numpy array files for my training. you are free to make your file(small task for you).




Thanks and njoy machine learning!.
