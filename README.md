# Neural Style Transfer with VGG19

## Project Overview

This project demonstrates Neural Style Transfer (NST) using a pre-trained VGG19 model in Keras. Neural Style Transfer allows you to blend the content of one image with the style of another, creating an entirely new artistic image that retains the structure of the content image while adopting the visual appearance of the style image.

## Features

1. Content Preservation: Maintains the structure of the original image.
2. Style Application: Applies artistic textures from another image.
3. Customizable Parameters: Adjust content/style weights for different effects.
4. Pre-trained VGG19 Model: Uses a well-trained network for feature extraction.

## Installation & Setup

### PrerequisiteS
Ensure you have Python 3.8+ installed along with the required dependencies.

### Steps to Run the Project

### 1.Clone the repository
git clone https://github.com/Dipti-24/Neural_Stylee_Transfer_P.git

cd Neural_Stylee_Transfer_P

### 2. Install dependencies
pip install -r requirements.txt  

### 3. Run the script
python style_transfer.py --content content.jpg --style style.jpg --output result.jpg  

### 4.View the output
The generated image will be saved as result.jpg.

## How It Works
The VGG19 model is used to extract content and style representations from the input images.
The content image contributes the structural elements, while the style image provides artistic textures.
An optimization process minimizes the difference between the output and the content/style representations.

## Future Enhancements
1. Multiple Style Transfer: Combine multiple styles into one output image.
2. Real-time Processing: Optimize the model for faster, real-time style transfer.
3. Web Interface: Develop a Streamlit/Flask web app for easy image uploads and style transfer.

## License
This project is licensed under the [MIT License](https://github.com/Dipti-24/Neural_Stylee_Transfer_P/blob/main/LICENSE).

## Contact
For any queries or collaboration opportunities, feel free to reach out:

  **Email** :mishradipti2402@gmail.com
  
 


