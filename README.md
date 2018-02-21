# Ex7_Image_compression_and_dimensionality_reduction

This programming exercise was done as part of Coursera's Machine Learning Course (Stanford University), taught by Prof. Andrew Ng.

## Image Compression

* Implement the K-means clustering algorithm to compress an image.
* Treating every pixel in the original image as a data example, the K-means algorithm was used to find the 16 colors that best group (cluster) the pixels in the 3D RGB space.
* Computed the cluster centroids on the image, and used the 16 colors to replace the pixels in the original image.

## Dimensionality reduction: Find a low-dimensional representation of face images

* Used principal component analysis to find a low-dimensional representation of face images.
* Normalized the dataset of face images, computed principal components, projected the data onto the principal components and reconstructed an approximation of the data
