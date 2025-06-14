# Deepfake Detection with MesoNet (Honours Project)

This project was developed as part of my Honours research and focuses on detecting deepfakes using the MesoNet (Meso4) model—a compact convolutional neural network designed specifically for identifying facial forgeries in images and videos.

## Overview

The goal of this project is to test how well a lightweight deepfake detection model performs across different datasets. I implemented Meso4 in TensorFlow/Keras, loaded pretrained weights, and evaluated its accuracy on real and fake facial image data.

Through this project, I worked through model integration, preprocessing pipelines, predictions, and visualising outputs to better understand the strengths and limitations of current detection models.

## Key Objectives

- Implement the Meso4 deepfake detection architecture
- Load and apply pretrained weights for prediction
- Test the model's generalisation by evaluating on varied datasets
- Analyse model outputs and understand common misclassifications

## Technologies Used

- Python (Used 3.10.4)
- TensorFlow (2.16.1) / Keras
- NumPy, Matplotlib
- Jupyter / VSCode


Make sure you have the correct folder structure and that the pretrained weights are saved as `.weights.h5` files in the correct path. Change file path to file directory of where the weights and data files are stored.

## About the Model

The Meso4 architecture is a compact CNN designed to detect subtle cues in manipulated facial images. It is particularly useful for low-resource environments where larger models may not be practical.

This implementation is based on:

Afchar, D., Nozick, V., Yamagishi, J., & Echizen, I. (2018). *MesoNet: a Compact Facial Video Forgery Detection Network*. IEEE WIFS.  
https://doi.org/10.1109/WIFS.2018.8630761
