# fashion_mnist_dataset
In this notebook, I have used unsupervised learning model to analyze the Fashion-MNIST dataset. The Fashion-MNIST dataset provided here consists of 60,000 images of clothing.
Each observation is a 28×28 pixel grayscale image, so each observation has 282 = 784 dimensions. There are 10 types of clothing in the dataset. The first column of the data matrix is the label of the observation, and all other columns are pixel intensities.

Objectives:

A) Data preprocessing includes data normalization, seperation of image features (pixel values) and label information. 

B) Due to limitations of system in handling large number of image dataset, random sample of size 2000 images are taken from the whole dataset.

C) To learn K-Means model with 10 clusters from randomly sampled observations.

D) Using PCA preprocessing to reduce data dimensions to 50 components and learn 2D t-SNE embeddings of observed data. And similarly visualize the clusterings from the previous part.

E) Observe how well the clusters from the previous part reflect the ground truth labels and the geometric relations
identified by t-SNE.
