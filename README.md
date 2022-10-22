# Eigenfaces
**Eigenfaces**

**In this project, we have tried to review [Face Recognition Using Eigenfaces: Matthew A. Turk 1991.](https://ieeexplore.ieee.org/document/139758)**

In this paper, an approach to the detection and identification of human faces is presented, and a working, near-real-time face recognition system which tracks a subject's head and then recognizes the person by comparing characteristics of the face to those of known individuals is described. This approach treats face recognition as a two-dimensional recognition problem, taking advantage of the fact that faces are normally upright and thus may be described by a small set of 2-D characteristic views. Face images are projected onto a feature space ('face space') that best encodes the variation among known face images. The face space is defined by the 'eigenfaces', which are the eigenvectors of the set of faces; they do not necessarily correspond to isolated features such as eyes, ears, and noses. The framework provides the ability to learn to recognize new faces in an unsupervised manner.

## **Dataset**
The data provided to you consists of 40 people's face photos taken in 10 different situations; from each of the first 30 people, randomly classify one photo as Train data and another photo as test data. We also saved one photo of each of the last ten people as data for the Detect Test.

 ![](https://github.com/Fateme-Azizabadi/Eigenfaces/blob/main/Images/Train.png)

 ![](https://github.com/Fateme-Azizabadi/Eigenfaces/blob/main/Images/Test.png)

 ![](https://github.com/Fateme-Azizabadi/Eigenfaces/blob/main/Images/Detect.png)

## **Result**

The mean of images:

 ![](https://github.com/Fateme-Azizabadi/Eigenfaces/blob/main/Images/mean.png)

The zero-mean of images:


 ![](https://github.com/Fateme-Azizabadi/Eigenfaces/blob/main/Images/Zero.Mean.png)

Reconstruction of train images with M=15


 ![](https://github.com/Fateme-Azizabadi/Eigenfaces/blob/main/Images/R.Train.png)

Recognizing the test data:


 ![](https://github.com/Fateme-Azizabadi/Eigenfaces/blob/main/Images/R.Test.png)




 
