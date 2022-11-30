# An exploratory analysis of data augmentation techniques 

This repository explores some **data augmentation** techniques to compare their impact on the accuracy of an image **classification model**. Data augmentation, as its name suggests, comprehends techniques used to increase the amount of data by adding modified copies of the original data or by creating synthetic data. It aims, not only to increase the size of the data to feed data-hungry models but also to enhance the quality of the training dataset since is it used to avoid overfitting (Shorten & Khoshgoftaar, 2019). 

There are many techniques, among them we can mention geometric transformations, color space augmentations, kernel filters, mixing images, random erasing, feature space augmentation, adversarial training, generative adversarial networks, and many others. We focus on four:

* Deep convolutional generative adversarial networks (DCGAN)
* Denoising autoencoder (DEA)
* Convolutional variational autoencoder (CVAE)
* Geometric transformations

We apply those techniques to four datasets from the MedMNIST (Yang et al., 2021) collection:

* PneumoniaMNIST
* BreastMNIST
* BloodMNIST
* DermaMNIST


> The code, methodology and results can be found at ```data_augmentation.ipynb```. 

> A more concise document explaining the methodology and results can be found in the ```main.pdf``` file.
 
 
