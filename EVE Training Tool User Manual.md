# EVE Training Tool

## Lunch View
![Settings Window](https://github.com/Hommoner/EVEAI/blob/master/images/Training%20Tool%231.png)

(A).Select EVE Run-Time Engine

(B).Click Button and wait for lunch finish. Tensorflow+Keras spend more time during first lunch.

## Project View
![Settings Window](https://github.com/Hommoner/EVEAI/blob/master/images/Training%20Tool%232.png)

If lunch finished successfully,UI will change to project view, here we can add new project or see trained projects.

(A).Show selected Porject infomation.

(B).Existing trainded peojcts, mouse left click to see imformation and mouse left double click to load selected proejct.

(C).Create new project to train new model.

(D).EVE Training Tool version and EVE Run-time engine version.

## Training Setup View
![Settings Window](https://github.com/Hommoner/EVEAI/blob/master/images/Training%20Tool%233.png)

(A).Model training and validate image folders and paramters. 

(B).Model Info for text input, preprocess parameters for increase train and validate images datasets.
Click button "Update" to change settings and click button "Preview" to see how preprocess parameters will effect original image(see image below).
<p align="center">
  <img width="512" src="https://github.com/Hommoner/EVEAI/blob/master/images/Training%20Tool%234.png">
</p>

(C).Click "Predict" button to check traind model performance.

(D).Click "Start Train"  button to strat train model. 

## Predict View
![Settings Window](https://github.com/Hommoner/EVEAI/blob/master/images/Training%20Tool%235.png)


(A).List all images from model training and validate image folders , click image name to show image in (D)

(B).Display heatmap option for assess whether a network is attending to correct parts of the image in order to generate a predict, this function is based on [keras-vis](https://raghakot.github.io/keras-vis/) . The result image is like:
<p align="center">
  <img width="512" src="https://github.com/Hommoner/EVEAI/blob/master/images/Training%20Tool%236.png">
</p>

## Training Status View
![Settings Window](https://github.com/Hommoner/EVEAI/blob/master/images/Training%20Tool%237.png)

Display current and best training result.
