# EVEAI
EVEAI is a Deep Learning Library based on python Keras and Tensorflow.
EVEAI dll allows embedding inference images from keras models into user-written applications. Under Windows, the EVEAI training Tool provides services to train user specific image datasets and EVEAI dll provides services to existing Windows applications which support inference images.

![Settings Window](https://github.com/Hommoner/EVEAI/blob/master/images/EVEAI%20flow.png)

Example code for:

LabVIEW/C++ builder/Visual Studio C++ (plan to:Delphi/CVI/Visual Studio C#)

## Installation
1. Installer for EVEAI runtime

    Download Link:[CPU tensorflow1.14.0 Version](https://sourceforge.net/projects/project-eveai/files/EVE%20Deep%20Learning%20Toolkit%20Installer%20CPU_1.14.0%2020200223.exe/download)
    
    *    No GPU needed but process speed is lower than GPU version.
    *    It's almost impossible for train models , but still usefual for predict.

    Download Link:[GPU tensorflow1.14.0 Version](https://sourceforge.net/projects/project-eveai/files/EVE%20Deep%20Learning%20Toolkit%20Installer%20GPU_1.14.0%2020200223.exe/download)

    *    Need Nvidia GPU Compute Capability > 3.5 [tensorflow link](https://www.tensorflow.org/install/gpu)
    *    Need NVIDIA Driver version > 410.x [Nvidia driver link](https://www.nvidia.com/Download/index.aspx?lang=en-us)
       
2. Installer for EVEAI training Tool ,EVEAI dll and example codes

    Download Link:[EVEAI](https://sourceforge.net/projects/project-eveai/files/EVE%20AI%2020200223.exe/download) 
    
    [User Manual](./EVE%20Training%20Tool%20User%20Manual.md)

3. Installer for Trained Examples:

    Download Link:[Fruilt 360 Image Dataset](https://sourceforge.net/projects/project-eveai/files/EVE%20Deep%20Learning%20Toolkit%20example%20for%20Fruit-360%20Installer.exe/download)
      
    Download Link:[Malaria Cell Image Dataset](https://sourceforge.net/projects/project-eveai/files/EVE%20Deep%20Learning%20Toolkit%20example%20for%20Malaria%20Cell%20Dataset%20Installer.exe/download)

    Download Link:[LEGO brick Image Dataset](https://sourceforge.net/projects/project-eveai/files/EVE%20Deep%20Learning%20Toolkit%20example%20for%20LEGO%20brick%20Dataset%20Installer.exe/download)

    Download Link:[Dogs and Cats Image Dataset](https://sourceforge.net/projects/project-eveai/files/EVE%20Deep%20Learning%20Toolkit%20example%20for%20Dogs%20and%20Cats%20Installer.exe/download)
      
    Download Link:[Flowers Image Dataset](https://sourceforge.net/projects/project-eveai/files/EVE%20Deep%20Learning%20Toolkit%20example%20for%20Flowers%20Installer.exe/download)

## Development
EVEAI dll is written in C++ Builder using Embarcadero RAD Studio 10.3.1 Rio Community Edition.

EVE AI run-time Executable is written in python packages into stand-alone executables by pyinstaller.
