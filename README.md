# Image-Processing-Using-GAN
This project applies neural style transfer techniques to blend the style of one image with the content of another using TensorFlow and the VGG19 model pre-trained on ImageNet. The style transfer model adjusts the style of the base image to reflect that of the style reference image while maintaining the original content.

Project Structure
base_image.jpeg - The content image (e.g., a photo of a person or landscape).
style_reference_image.jpeg - The style image (e.g., a famous painting).
style_transfer.py - Python script that performs style transfer.
requirements.txt - List of Python packages required to run the project.
Setup and Installation
Ensure Python 3.8 or newer is installed on your machine. You can download it from python.org.

Clone the repository:
git clone https://your-repository-url.git
cd your-project-directory
Install required packages:
pip install -r requirements.txt
Running the Script
Prepare your images:
Place your content and style images in the project directory or update the paths in the script accordingly.
Execute the script:
Run the following command:
python style_transfer.py
View the results:
The generated images will be saved periodically and at the end of the iteration process. They can be found in the project directory.
Customization
You can adjust the weights for content, style, and total variation loss in the script to see how they affect the output.
Modify the iterations variable to increase or decrease the number of iterations for which the style transfer runs.
Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your proposed changes.
