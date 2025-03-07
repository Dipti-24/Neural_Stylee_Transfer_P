# Neural Style Transfer with VGG19

## Project Overview

This project demonstrates Neural Style Transfer (NST) using a pre-trained VGG19 model in Keras. Neural Style Transfer allows you to blend the content of one image with the style of another, creating an entirely new artistic image that retains the structure of the content image while adopting the visual appearance of the style image.

## Features

1. Content Preservation: Maintains the structure of the original image.
2. Style Application: Applies artistic textures from another image.
3. Customizable Parameters: Adjust content/style weights for different effects.
4. Pre-trained VGG19 Model: Uses a well-trained network for feature extraction.

## Tech Stack
1. Python
2. TensorFlow
3. NumPy
4. Matplotlib
5. Keras
   

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
python style_transfer.py 

### 4.View the output
The generated image will be saved as result.jpg.

## How It Works
The VGG19 model is used to extract content and style representations from the input images.
1. The content image contributes the structural elements, which are captured using content loss, typically computed as the difference between feature maps of the content and generated images.
2. The style image provides artistic textures, which are represented using the Gram matrix of feature maps. The difference between the Gram matrices of the style and generated images is minimized using style loss.
3. An optimization process updates the generated image to minimize the content loss and style loss, ensuring that the final output preserves the structure of the content image while adopting the textures of the style image.
   
## Future Enhancements
1. Multiple Style Transfer: Combine multiple styles into one output image.
2. Real-time Processing: Optimize the model for faster, real-time style transfer.
3. Web Interface: Develop a Streamlit/Flask web app for easy image uploads and style transfer.

## License
This project is licensed under the [MIT License](https://github.com/Dipti-24/Neural_Stylee_Transfer_P/blob/main/LICENSE).

## Contact
For any queries or collaboration opportunities, feel free to reach out:

  **Email** :mishradipti2402@gmail.com
  
 


