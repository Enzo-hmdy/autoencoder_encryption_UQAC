# Image Encryption Using Autoencoders

## Overview

This project aims to demonstrate whether an autoencoder can be used to encrypt images. An autoencoder is a type of neural network that learns to compress and then reconstruct data. In this case, we use it to encode images into a latent space representation, which can be considered an encrypted form of the image. We compare the results against classic cryptographic algorithms, such as AES, RSA, Twofish, and ChaCha20.

## Table of contents

1. [Installation](#installation)
2. [tensorflow](#tensorflow)
3. [Usage](#usage)



## Installation

To install the required dependencies, run the following command:

```bash
git clone https://github.com/Enzo-hmdy/autoencoder_encryption_UQAC
cd autoencoder-for-images-encryption
pip install -r requirements.txt
```

The requiement doesn't include tensorflow, as explained later in the readm.

Then you are free to run the juptyer notebook as you wish. If there are any missing dependecies feel free to install them using pip and notifiy me so i can update the requirements.txt file.

If you want to find the  dowsample version of the dataset you can find it [here](https://github.com/quanhua92/downsampled-open-images-v4), i invite you to use this one it's gonna save you some download time. 

<div style="background-color: #fff3cd; border: 1px solid #ffeeba; padding: 10px; border-radius: 5px;">
  <strong>Warning</strong> 
</div>

you might experience issues with tensorflow if you haven't set or install it on your device. If you are using a GPU you might want to install the GPU version of tensorflow and here should be 2 cases : 

1- You run linux and you have a GPU that supports CUDA and cuDNN, you can install the GPU version of tensorflow by running the following command without any problem : 

```bash
pip install tensorflow-gpuZ
```

2- You are using windows and you have a GPU that supports CUDA and cuDNN, you can finds some information on how to proceds on these differents links : 

https://www.tensorflow.org/install/pip?hl=fr#windows-native

https://melika-sce.medium.com/step-by-step-guide-to-setup-tensorflow-with-gpu-support-on-windows-10-ad3a492ac67f

 ( you can also install it on WSL )


## Usage

To run the code, you can simply open the Jupyter notebook and run each cell. The notebook is divided into sections, each of which corresponds to a different part of the project. All the code is documented, so you should be able to follow along easily. I do recommand to run the code on a GPU if you have one, it's gonna save you some time.

