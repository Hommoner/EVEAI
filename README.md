# EVEAI
EVEAI is a Deep Learning Library based on python Keras and Tensorflow.
EVEAI dll allows embedding inference images from keras models into user-written applications. Under Windows, the EVEAI training Tool provides services to train user specific image datasets and EVEAI dll provides services to existing Windows applications which support inference images.

## Vision Applications

### Image Classification:
Assigning a label to an image, for example:Labeling an image is a cat or a dog.

![Settings Window](https://github.com/Hommoner/EVEAI/blob/master/images/EVEAI%20flow.png)


### Semantic Segmentation
Segmenting pixels in an image to different categories of object, for example: street view image segmentation.

![Settings Window](https://github.com/Hommoner/EVEAI/blob/master/images/EVEAI%20Semantic%20Segmentation.png)

this demo images are from[ KITTI VISUAL ODOMETRY DATASET](http://cvlibs.net/datasets/kitti/eval_semantics.php)

### Object Detection(MaskRCNN) (only inference,working for annotation tool)
Tracking multiple objects in an image,for example: real-time tracking chinese chess positions.
This algorithm source code is written by [fizyr](https://github.com/fizyr/keras-maskrcnn)

![Settings Window](https://github.com/Hommoner/EVEAI/blob/master/images/EVEAI%20Object%20Detection(MaskRCNN).png)

[![Chinese Chess](https://github.com/Hommoner/EVEAI/blob/master/images/EVEAI%20MaskRCNN%20Chinese%20Chess.png)](https://youtu.be/7JZAZnk6Gss)

## Installation
1. Installer for EVEAI runtime

    Download Link:[CPU tensorflow1.14.0 Version](https://drive.google.com/open?id=18nIOy_KUyxRPplRRAdWRaQlom9xRzoJc)
    
    *    No GPU needed but process speed is lower than GPU version.
    *    It's almost impossible for train models , but still usefual for predict.

    Download Link:[GPU tensorflow1.14.0 Version](https://drive.google.com/open?id=1sYGX3prK07pqgQ5TjFnasn5MRXYKUIxR)

    *    Need Nvidia GPU Compute Capability > 3.5 [tensorflow link](https://www.tensorflow.org/install/gpu)
    *    Need NVIDIA Driver version > 410.x [Nvidia driver link](https://www.nvidia.com/Download/index.aspx?lang=en-us)
       
2. Installer for EVEAI training Tool ,EVEAI dll and example codes

    Download Link:[EVEAI](https://drive.google.com/file/d/1mE-9S1zeIJWiObLMTza4P1eBYdKMS0s2/view?usp=sharing) 
    
    [User Manual](./EVE%20Training%20Tool%20User%20Manual.md)

3. Installer for Trained Examples:

### Image Classification:
Download Link:[Fruilt 360 Image Dataset](https://sourceforge.net/projects/project-eveai/files/EVE%20Deep%20Learning%20Toolkit%20example%20for%20Fruit-360%20Installer.exe/download)
      
Download Link:[Malaria Cell Image Dataset](https://sourceforge.net/projects/project-eveai/files/EVE%20Deep%20Learning%20Toolkit%20example%20for%20Malaria%20Cell%20Dataset%20Installer.exe/download)

Download Link:[LEGO brick Image Dataset](https://sourceforge.net/projects/project-eveai/files/EVE%20Deep%20Learning%20Toolkit%20example%20for%20LEGO%20brick%20Dataset%20Installer.exe/download)

Download Link:[Dogs and Cats Image Dataset](https://sourceforge.net/projects/project-eveai/files/EVE%20Deep%20Learning%20Toolkit%20example%20for%20Dogs%20and%20Cats%20Installer.exe/download)
      
Download Link:[Flowers Image Dataset](https://sourceforge.net/projects/project-eveai/files/EVE%20Deep%20Learning%20Toolkit%20example%20for%20Flowers%20Installer.exe/download)

### Semantic Segmentation
Download Link:[Car Video Dataset](https://drive.google.com/open?id=1Tox_ZpiqXi9COaNw98UmcrApVSlFcWUV)
![Settings Window](https://github.com/Hommoner/EVEAI/blob/master/images/Seg03.png)
    
Download Link:[KolektorSDD Dataset](https://drive.google.com/open?id=1yqYOW8fUMXjGdLKWiPjlKGIW5rqv4SkL)
this images are from[Visual Cognitive Systems Laboratory](https://www.vicos.si/Downloads/KolektorSDD)
    
![Settings Window](https://github.com/Hommoner/EVEAI/blob/master/images/Seg01.png)
![Settings Window](https://github.com/Hommoner/EVEAI/blob/master/images/Seg02.png)
    
### Object Detection(MaskRCNN)
Download Link:[Chinese Chess Dataset](https://drive.google.com/open?id=1CF2oOOiepQ3l4Gx8K-ub4zheNUtyk_7y)

### Example code

LabVIEW
(https://youtu.be/baybKe7CMdU)

C++ builder
(https://youtu.be/2BYF84C7bdE)


Visual Studio C++ 
(plan to:Delphi/CVI/Visual Studio C#)

## Development
EVEAI dll is written in C++ Builder using Embarcadero RAD Studio 10.3.1 Rio Community Edition.

EVE AI run-time Executable is written in python packages into stand-alone executables by pyinstaller.
