# Colour-Detection-using-Data-Science

This repository contains code and resources for training and using a Convolutional Neural Network (CNN) model to detect brain tumours. The model is implemented using Python and TensorFlow, and it can be executed in Google Colab.

# Prerequsites
To run the code, you need the following prerequisites:
+ Python 3.x
+ OpenCV (cv2)
+ NumPy
+ scikit-learn



# Installation
1. Clone the repository:
   ```
   git clone <repository_url>
   cd <repository_name>
   ```
   
3. Install the required dependencies:
   ```
   pip install opencv-python numpy scikit-learn
   ```

# Usage
1. Dataset Preparation:
    + Organize your labeled dataset in subdirectories, where each subdirectory represents a color category.
    + Replace the 'path_to_dataset' variable in the code with the path to your labeled dataset.

2. Training the Color Detection Model:
    + Run the code to load and preprocess the dataset.
    + Train the KNN classifier on the dataset.
    + The accuracy of the classifier on the test set will be displayed.

3. Performing Color Detection on an Image:
    + Replace 'path_to_image' in the code with the path to the image for color detection.
    + Run the code to load the image and extract color features.
    + The predicted color of the image will be displayed.

# For Colab users
1. Download the zip file "Color_images_labelled.zip" for training the model and image file "1429590.jpg" for testing the model, these are available in this repository.
2. Open the zip file in your system and extract the sub-folder by copying it and pasting to any relevant folder in your computer system.
3. Open colab and upload the extracted folder as it is. Also upload the "1429590.jpg" image.
4. Copy the code from "Code.py" file and paste it on the cell of colab.
5. Run the cell to see the output.
6. You can check the result by uploading any other relevant image of your choice and then replacing the test file with it.

# Contributing
Contributions to this project are welcome. Feel free to open issues for any questions or problems you encounter. If you have any suggestions for improvements or new features, you can also submit pull requests.

# License
This project is licensed under the [MIT License](https://github.com/adithyarangarajan783/Colour-Detection-using-Data-Science/blob/main/LICENSE)
