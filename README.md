# Evolutionary Strategies for Domain Adaptation
This study includes four expriments on MNIST,MNIST-M and Office31 datasets. Convolutional Neural Network is used for creating features and RandomForest Classifier for prediction.  In evolutionary process,it is used SNES(separable evolution strategies), adapting the weights of the neural network.

## MNIST and MNIST-M experiment
The `Mnist_Mnistm_DomainAdaptation.ipynb` is the domain adaptation code. The MNIST-M dataset consists of MNIST digits blended with random color patches from the [BSDS500](http://www.eecs.berkeley.edu/Research/Projects/CS/vision/grouping/resources.html#bsds500) dataset. To generate a MNIST-M dataset, first download the BSDS500 dataset and run the `create_mnistm.py`. 

This may take a couple minutes and should result in a `mnistm_data.pkl` file containing generated images.

## Office-31 experiments

There is three experiment file for the same dataset. `Amazon_Webcam_DomainAdaptation.ipynb`, Amazon as a source domain and Webcam as a target domain. `Dslr_Webcam_DomainAdaptation.ipynb` Dslr as a source domain and Webcam as a target domain. `Webcam_Dslr_DomainAdaptation.ipynb` Webcam as a source domain and Dslr as a target domain. For working these files need to  download the [Office-31](https://drive.google.com/file/d/0B4IapRTv9pJ1WGZVd1VDMmhwdlE/view).
