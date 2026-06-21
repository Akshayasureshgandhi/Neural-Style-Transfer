# Neural Style Transfer using TensorFlow

## Project Overview

This project implements Neural Style Transfer (NST) using TensorFlow and a pre-trained VGG19 model. The application combines the content of one image with the artistic style of another image to generate a new stylized image.

## Features

* Load content and style images
* Extract image features using VGG19
* Compute Content Loss and Style Loss
* Use Gram Matrix for style representation
* Generate stylized output image
* Save the generated image

## Technologies Used

* Python
* TensorFlow
* VGG19
* NumPy
* Matplotlib
* Pillow
* Jupyter Notebook

## How Neural Style Transfer Works

1. Load a content image and a style image.
2. Use a pre-trained VGG19 model to extract image features.
3. Compute:

   * Content Loss (preserves image structure)
   * Style Loss (captures artistic style)
4. Optimize a generated image using gradient descent.
5. Save the final stylized image.

## Concepts Used

* Deep Learning
* Transfer Learning
* Computer Vision
* Convolutional Neural Networks (CNN)
* Feature Extraction
* Gram Matrix
* Gradient Descent

## Future Improvements

* Flask Web Application
* Multiple Artistic Styles
* Real-Time Style Transfer
* Azure Deployment
* User Image Upload Interface

## Author

Akshaya S

GitHub: https://github.com/Akshayasureshgandhi
