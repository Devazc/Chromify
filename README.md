# Chromify
### Chromify: The Black and White Image Colorizer

**Project Initial Commit: Black and white image colorization with OpenCV and Deep Learning**

## Overview

This project aims to develop a deep learning model that can colorize black and white images. The model can be trained on a large dataset of colored images, and then used to predict the color values for a grayscale image. The project will involve exploring different deep learning techniques like GANs, autoencoders, etc., and optimizing the model's performance.

## Dependencies

- Python 3.x
- OpenCV
- NumPy

## Installation

1. Clone this repository: `git clone https://github.com/Devazc/Chromify.git`
2. Install the dependencies: `pip install opencv-python numpy tensorflow`
3. Download the dataset of colored images and grayscale images. You can use a dataset like ImageNet or COCO.
4. Preprocess the dataset to convert the colored images to grayscale and save them in a separate folder.
5. Train the model using the preprocessed dataset.
6. Test the model on a sample black and white image.

## Usage

To train the model, run the following command:

`python train.py --dataset <path_to_dataset> --epochs <num_epochs> --batch_size <batch_size>`


To test the model on a black and white image, run the following command:

`python predict.py --model <path_to_saved_model> --image <path_to_bw_image>`


## Future Work

In the future, I plan to improve the model's performance by exploring different deep learning techniques and hyperparameters. Also plan to deploy the model on Hugging Face Spaces, so that it can be used by other users for colorizing their own images. Stay tuned for updates!





