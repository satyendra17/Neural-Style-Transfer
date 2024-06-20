# Neural-Style-Transfer
Neural style transfer is a powerful application of deep learning that merges the content of one image with the artistic style of another. 

Neural Style Transfer Project
Overview
This project implements neural style transfer using TensorFlow and VGG19, allowing you to merge the content of one image with the artistic style of another. Neural style transfer is achieved by optimizing a loss function that balances content preservation and style transfer, resulting in visually appealing images that combine the structure of a base content image with the style of a reference style image.

Requirements
Python 3.x
TensorFlow 2.x
NumPy
Matplotlib
Pillow
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your_username/neural-style-transfer.git
cd neural-style-transfer
Install dependencies using pip:

bash
Copy code
pip install -r requirements.txt
Usage
1. Setting Up
Place your content image (kohli.jpg) and style image (mosaic.jpg) in the respective directories (content and style) within the project directory.

Results
Generated images will be saved periodically during training and can be viewed to monitor the style transfer progress. Adjustments to the style transfer parameters can be made to achieve different artistic effects.

Acknowledgments
This project utilizes the VGG19 model pretrained on ImageNet, courtesy of the TensorFlow Keras API.
Inspiration and guidance drawn from various sources on neural style transfer implementations.
License
This project is licensed under the MIT License - see the LICENSE file for details.
