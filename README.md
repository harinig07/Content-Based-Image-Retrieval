# Content-Based-Image-Retrieval
Image retrieval is a process of searching and retrieving digitalimages based on the content described by the various features, shape and other visual information. With the help of this content, users are able to search for images from a large collection quickly.

## Methodology
### 1. Creating Image Database:
  - Get pool of images and extract the feature of images using SIFT
  - Cluster the features using KMeans
### 2. Creating visual representation:
  - Use bag of words, TF-IDF as a visual representation of the extracted features
### 3. Image querying and evaluation:
  - Extract the features of query image
  - Compute the distance between feature representation of query image and representations of image datatbase
  - Compute evaluation metrics on retrieved images

## Dataset
<img width="487" alt="Dataset" src="https://user-images.githubusercontent.com/128280752/226164626-ae8073c6-6917-4fc1-9800-83a3d04e8942.PNG">

