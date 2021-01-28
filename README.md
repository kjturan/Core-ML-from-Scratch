# Core-ML-from-Scratch

This repository exhibits a selection of concepts fundamental to Machine Learning. All of the implementation is done from scratch,
soley using Numpy and (occassionally) Pytorch. 

- scratch_1.ipynb demonstrates linear and polynomial regression, pca and k-means clustering, linear and logistic regression, and 
  a basic neural network on the IRIS and MNIST datasets (dataset_1)

- scratch_2.ipynb demonstrates basic convolutions, convolutional pyramidal AutoEncoders, Variational AutoEncoders (VAE), and VGGs 
  on the CelebA and MNIST datasets (dataset_2)
  
I have provided a zipped file for dataset_1, but dataset_2 is far too large so please refer to the following link: 'https://drive.google.com/u/0/uc?export=download&confirm=Dv2h&id=1cRSxlp7RJWoggAaV3clD_MQfPyMkvCCV'. After downloading you can expect to see the following directory structures:
```
+-- dataset_1/
|  +-- IRIS/
|  |   +-- iris_train_labels.npy
|  |   +-- iris_test_labels.npy
|  +-- MNIST/
|  |   +-- mnist_train_labels.npy
|  |   +-- mnist_test_labels.npy
  
+-- dataset_2/ 
|  +-- CelebA/
|  |   +-- train/
|  |   |   +-- 0.png
|  |   |   +-- 1.png
|  |   |   +-- ...
|  |   +-- validation/
|  |   |   +-- 0.png
|  |   |   +-- 1.png
|  |   |   +-- ...
|  +-- Denoising/
|  |   +-- input_noisy_images
|  |   +-- target_clean_images
|  +-- Filtering/
|  |   +-- audio.npy
|  |   +-- image.png
|  |   +-- noisy_image.png
|  +-- MNIST/
|  |   +-- train/
|  |   |   +-- 0.png
|  |   |   +-- 1.png
|  |   |   +-- ...
|  |   +-- validation/
|  |   |   +-- 0.png
|  |   |   +-- 1.png
|  |   |   +-- ...

```
To run the notebooks, please download the correct datasets and organize the project such that the dataset and trained model folders 
should be one level above your notebook - that is, "../Datasets", "../trained_models" etc.  

```
   Suggested directory structure:  
   
   Root Folder/  
   +-- Models/ 
   +-- Datasets/  
   |   +-- dataset_1/
   |   |   +-- IRIS
   |   |   +-- MNIST
   |   +-- dataset_2/ 
   |   |   +-- MNIST
   |   |   +-- CelebA
   +-- Src/  
   |   +-- scratch_1.ipynb 
   |   +-- scratch_2.ipynb
 
 ```
       
Note: the file format of MNIST is different in both datasets. 

Feel free to email me regarding any inquires @kaanjenkinsturan@gmail.com
