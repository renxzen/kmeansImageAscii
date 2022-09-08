# Image Asciifier

Thought i uploaded this project i made, while having fun implementing my own version of K-Means. I applied this algorithm to compress an image, then make it ASCII with some character replacements.

## K-Means

K-Means clustering is an unsupervised machine learning algorithm which means that we only have inputs and not outputs. It tries to group the data into clusters based on their similarity. Using this algorithm we have to specify the number of clusters we want the data to be divided into. I added a new method to calculate the SSE (Sum of Squared Euclidean distances) to find the initial centroids, to minimize the needed iterations in total.

## Test on the Iris Dataset

Quick 2D implementation for better visualization

![](img/001.png)

## Test on an image from Invincible

Original

![](img/002.png)

Resized image and k-means=7 applied

![](img/003.png)

Asciified image with random characters

![](img/004.png)
