# **Position Reconstruction using PMTs waveforms from CYGNO LIME 2 detector**

* The idea of this project came from a laboratory activity done in Laboratori Nazionali di Frascati, based on the CYGNO experiment for Directional Dark Matter search. 
* The main goal is to study the behaviour and efficiency of two possible Neural Network architectures able to analyze the waveforms extracted from 4 PMTs, positioned at the corners of a squared-based cone, when a particle crosses the detector.
* A possible application of such a Neural Network is the 3D reconstruction of the particle's track, if combined with the images from the LIME Time Projection Chamber. Neveretheless, this part will not be covered in this project, since it would require appropriate data analysis from the underground facility in Laboratori Nazionali del Gran Sasso.
* The network study is expanded with a **toy model simulation**, and the results are presented as squared **RMSE-colormaps** which are able to provide at glance the network's predictions precision over the scanned regions.

The dataset used to train the networks can be found on [Google Drive](https://drive.google.com/drive/folders/1-3Ghqj2Ps7Avec3rxHVLbOZatDtLko-8?usp=sharing), along with a .csv file used to keep track of the target positions scanned in the various runs. \\
Moreover, a folder containg some relevant pre-trained models can be found at the same link. \\
In order for the code to work, **please add a shortcut to this folder on your main GDrive folder**.

```
Code by Luca Zappaterra, last modified: 11/07/2022
```

