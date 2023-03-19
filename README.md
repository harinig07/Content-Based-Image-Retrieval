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
The query image given from the wang and malayakew dataset is
<p align="center">
<img width="285" alt="Capture" src="https://user-images.githubusercontent.com/128280752/226165448-1a3a38a3-2e04-4d15-8f7b-5d71aca6f070.PNG">
</p>
<p align="center">
<img width="194" alt="Capture" src="https://user-images.githubusercontent.com/128280752/226165884-5e2acbd8-fc88-44b1-9897-957cdbd119d9.PNG">
</p>

10 retrieved images with histograms from both datasets is shown.
<p align="center">
<img width="490" alt="Capture" src="https://user-images.githubusercontent.com/128280752/226165043-85ca115d-9ab9-471c-a962-2c18704685a2.PNG">
</p>

