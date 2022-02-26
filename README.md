# Face Recognition with Keras 
This repository contains the script to detect the face with keras.
Given the images, the program compares and detects the similarity of human faces based on
the calculated scores.

## Libraries
- keras: 2.4.3

## Model
The analysis is based on a pretrained model, called "vgg_face_weights.h5". 
The model scores for each face are vectors. Based on those vectors, we calculate
the similarity between the scores of two faces using Cosine Similarity and Euclidean Distance
in order to identify if two faces are the same person.

## Usage
- `face_recognition_with_keras.ipynb` is the jupyter notebook for this project.

