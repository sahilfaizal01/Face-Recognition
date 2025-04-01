# Face-Recognition

## Traditional Methods to Face Recognition
### 1. Eigenfaces - 
Utilized Principal Component Analysis (PCA) to extract facial features and identify individuals based on eigenvalues and eigenvectors of the face images
### 2. Fisherfaces - 
Similar to Eigenfaces, but uses Fisher's Linear Discriminant Analysis (LDA) to improve discrimination between different individuals
### 3. Local Binary Patterns Algorithm (LBPH) - 
* A popular and robust method for face recognition, which extracts local texture information from facial images, encoding patterns and their relationships into a histogram representation.
* LBPH is computationally efficient and works well with facial images exhibiting variations in lighting conditions and facial expressions.

## State-of-the-Art Models for Face Recognition
Face recognition technology has witnessed significant advancements in recent years, driven by breakthroughs in deep learning and the availability of large-scale annoted datasets. State-of-the-art models have pushed the boundaries of face recognition accuracy, robustness, and efficiency. Some of the notable state-of-the-art models for face recognition are:
### 1. FaceNet:
* Introduced the concept of triplet loss for learning face embeddings.
* By training a deep convolutiona neural network (CNN) to map face images into a high-dimensional feature space, FaceNet achieved impressive results in face recognition.
* It learns to encode faces in such a way that similar faces are closer together in the embedding space, facilitating efficient face matching.
### 2. DeepFace:
* A deep learning model based on multi-layer CNN architecture, which acheved remarkable performance by training on a large-scale dataset and employing a vast number of labeled identities.
* DeepFace integrates both indentification and verification tasks, making it suitable for various face recognition applications.
### 3. ArcFace:
* Introduced the additive angular margin loss to improve face recognition accuracy and discrimination.
* By incorporating angular margin-based supervision into the CNN training process, ArcFace effectively enhances the inter-class separability of face embeddings.
* It achieves SOTA performance on benchmark face recognition datasets
### 4. VGGFace and VGGFace2:
* These models employ deep convolutional networks with multiple layers to extract discriminative features from face images.
* VGGFace and VGGFace2 have demonstrated impressive performance in face recognition, particularly when trained on large-scale datasets.
### 5. DeepID: 
* Focuses on learning identity-specific features using multiple deep neural networks. It incorporates both verification and identification tasks to improve discrimination between faces.
* DeepID has shown strong performance in face recognition, particularly in scenarios with significant variations in post, illumination, and expression. 

## Tools Used:
### 1. DLib - 
* A powerful open-source library that offers face detection, landmark estimation, and face recognition capabilities.
* It utilizes deep learning-based models, such as the ResNet network, to achieve high accuracy in face recognition tasks.
* The library provides pre-trained models for face recognition, simplifying the implementation process.
