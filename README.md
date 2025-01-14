# Gender and Age Detection with OpenCV and Deep Learning

This project implements a **Gender and Age Detection** system using **Convolutional Neural Networks (CNN)** and **OpenCV**. The model can predict a person's gender and age group from a single image of their face with high accuracy (95%) using the **Adience Dataset**.

## Table of Contents

- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Setup](#setup)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Introduction

The objective of this project is to classify a person's gender (Male/Female) and age into one of the following ranges:
- (0 – 2)
- (4 – 6)
- (8 – 12)
- (15 – 20)
- (25 – 32)
- (38 – 43)
- (48 – 53)
- (60 – 100)

This system uses **Deep Learning** models pre-trained on the **Adience Dataset** and utilizes **OpenCV** for face detection. The model processes images or video streams in real-time, displaying the predicted gender and age on the image.

## Technologies Used

- **Python**
- **OpenCV** for real-time image and video processing
- **TensorFlow** for deep learning model training and inference
- **Caffe** for the pre-trained model used in gender and age detection
- **Convolutional Neural Networks (CNN)** for image classification
- **Adience Dataset** for training and testing the model
- **Protocol Buffers (protobuf)** for model configuration and trained weights
- **Argparse** for command-line argument parsing
- **NumPy** for numerical data handling

## Dataset

The model is trained on the **Adience Dataset**, a public domain dataset with over **26,000 images** of faces in various real-world conditions. The dataset includes images from Flickr albums under the Creative Commons license and covers a range of ages and gender identities. The dataset can be found [here](http://www.openu.ac.il/home/hassner/projects/cnn_age_gender/).

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/shashwatmurawala/Gender-and-Age-Detection.git
   cd gender-age-detection
