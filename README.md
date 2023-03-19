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
  
<img width="750" alt="methodology" src="https://user-images.githubusercontent.com/128280752/226164702-6b7ee8f2-a774-47a0-aa5f-8f97dad71471.png">

## Dataset
The dataset used are Wang and Malayakew datatset. In Malyakew datatset only 10 classes , consisiting of 50 images in each class is consisdered.

## Results
10 retrieved images with histograms from both datasets is shown.


