# GAN Implementation for COMP7502

This repository include the implementation of `Vanilla GAN`, `DCGAN` and `WGAN`.

## Data
First download the dataset from :

https://github.com/jbencina/simpsons-image-training-dataset

This dataset include 30,693 frames from Simpsons episodes. In this Demo, 2,488 images which contain only Marge, Homer, Lisa, or Bart were used. Please use images in "faces-clean-color".

Put the data in `./data/simpsons/`.

## Prerequisites
* Python 2.7 or Python 3.3+
* Tensorflow 1.4.0

## Usage
```
python VGAN.py
python DCGAN.py
python WGAN.py
```

## Credits
The credits for most of the code go to [LynnHo](https://github.com/LynnHo/DCGAN-LSGAN-WGAN-WGAN-GP-Tensorflow). This is merely a wrapper with Vanilla GAN implementation, which is modified from [wiseodd](https://github.com/wiseodd/generative-models/blob/master/GAN/vanilla_gan/gan_tensorflow.py).