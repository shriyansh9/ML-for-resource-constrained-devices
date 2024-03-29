# ML-for-resource-constrained-devices
Presently large amount of data is available everywhere and Machine Learning algorithms help us to analyze and extract useful information based on this analysis. But most of conventional Machine learning algorithms require lots of computational power and storage space, which wouldn’t have been a problem if we had sufficient resources like cloud. But there are many real world applications which require real time prediction on devices that are severely resource-constrained. Such applications demand model to use small storage and consume less computing power. 
In this project, we have focused our work on K-Nearest Neighbor Classifier and tried to improvise on these models, so as to reduce the storage requirement of such models and use less computing power(prediction time) without compromising significantly on accuracy. Some approaches that we used to reduce the data size were projecting data onto low dimensional space using PCA and TSNE, and another one uses sampling for the same without compromising much on the prediction accuracy.

## Dataset
For our task we are using **MNIST** dataset containing 60000 sample images of handwritten digits of size 28x28. 

## Approaches
- Protoype Based Classification
- Prototype Based Classification with Dimensionality Reduction
- k-NN on PCA features
- Centroid of each class as landmark
- Random landmark points
- k-NN using similarity instead of euclidean distance
- k-NN using similarity (with PCA)
