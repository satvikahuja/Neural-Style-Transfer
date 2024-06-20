# Neural Style Transfer with VGG19

This project implements neural style transfer using a pre-trained VGG19 model. The process involves transferring the style of one image onto another while preserving the content of the latter.

## Prerequisites

Make sure you have the following libraries installed:
- torch
- torchvision
- numpy
- matplotlib
- opencv-python
- pillow

You can install them using pip:

pip install torch torchvision numpy matplotlib opencv-python pillow

## Steps

### Import Libraries and Load Model

Import necessary libraries and load the pre-trained VGG19 model.

### Set Device

Set the device for computation (CPU or GPU).

### Load Images

Load the content and style images using OpenCV.

### Resize Images

Resize the images to a suitable size for processing.

### Visualize Images

Visualize the content, target, and style images using Matplotlib.

### Extract Feature Maps

Extract feature maps from the VGG19 model for both content and style images.

### Compute Gram Matrix

Compute the Gram matrix for style representation.

### Run Style Transfer

Optimize the target image to match the content and style representations.

### Visualize Result

Visualize the final stylized image alongside the content and style images.

## Results

### Content Image
<img width="757" alt="content" src="https://github.com/satvikahuja/Neural-Style-Transfer/assets/109898261/b8d4da82-ea45-4f23-8d59-9be2935ca53d">


### Style Image
<img width="736" alt="style" src="https://github.com/satvikahuja/Neural-Style-Transfer/assets/109898261/9d777828-b0cb-462d-b8ea-0acae7598588">


### Result Image
<img width="736" alt="Screenshot 2024-06-21 at 12 29 51 AM" src="https://github.com/satvikahuja/Neural-Style-Transfer/assets/109898261/8def2882-866f-4f20-a2a3-dee6589ee7c7">


Feel free to replace the placeholders with your actual images and paths.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
