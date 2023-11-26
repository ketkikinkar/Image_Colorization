
# Pix2Pix - Image Colorization with Conditional WGAN

## Overview
This Jupyter Notebook demonstrates the use of a Pix2Pix model enhanced with a Conditional Wasserstein Generative Adversarial Network (WGAN) for the task of image colorization. It explores advanced techniques in deep learning to add color to grayscale images, leveraging the stability and efficiency of WGANs.

## Introduction
Pix2Pix is renowned for its proficiency in image-to-image translation tasks. This notebook takes it a step further by integrating a WGAN with a U-Net architecture based on residual blocks, improving its performance in colorization. The U-Net architecture, known for its effectiveness in image segmentation, combined with the stability of WGANs, makes for a robust solution to colorization challenges.

## Architecture

![alt text](https://github.com/ZoreAnuj/Image_Colorization/blob/main/pix2pix_arch.png)


## Features
- Implementation of Pix2Pix with Conditional WGAN.
- Detailed exploration of U-Net architecture with residual blocks.
- Demonstrations of image colorization on various grayscale images.
- Interactive user interface for image uploads and processing.

## Prerequisites
- Python 3.x
- TensorFlow 2.x
- OpenCV for image transformations
- Matplotlib for visualization
- Torchsummary for model summaries
- Additional dependencies as listed in `requirements.txt`.

## Installation
1. Clone the repository: `git clone [repository URL]`
2. Install dependencies: `pip install -r requirements.txt`
3. Run `!pip install torchsummary` within the notebook for model summaries.

## Usage
1. Launch the notebook: `jupyter notebook pix2pix-image-colorization-with-conditional-wgan.ipynb`
2. Follow the detailed sections on data loading, preprocessing, and model architecture.
3. Experiment with colorizing your own grayscale images in the interactive section.

## Notebook Structure
- Project Understanding and Goals
- Insights into Image Colorization Techniques
- Data Loading and Preprocessing
- Model Architecture: Generator and Discriminator in detail
- Training the Conditional WGAN
- Interactive Image Colorization Demo

## Dataset Sample



## Results

### Epoch 0 
![alt text](https://github.com/ZoreAnuj/Image_Colorization/blob/main/epoch0.png)

### Epoch 10
![alt text](https://github.com/ZoreAnuj/Image_Colorization/blob/main/epoch10.png)

### Epoch 20
![alt text](https://github.com/ZoreAnuj/Image_Colorization/blob/main/epoch20.png)

### Epoch 70
![alt text](https://github.com/ZoreAnuj/Image_Colorization/blob/main/spoch_70.png)

### Epoch 120
![alt text](https://github.com/ZoreAnuj/Image_Colorization/blob/main/epoch_120.png)

### Result

![alt text](https://github.com/ZoreAnuj/Image_Colorization/blob/main/sample.png)

## Contributing
Your contributions are welcome! Please adhere to the standard pull request process for any improvements or bug fixes.

