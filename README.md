# image-forgery-detection

Image Forgery Detection Using Deep Learning
This is a repository for the implementation of a deep learning model for detecting image forgery. The model uses a convolutional neural network (CNN) architecture to classify an input image as authentic or forged.

### Installation
To use this repository, you will need to have Python 3 installed, along with the following libraries:

TensorFlow
NumPy
Matplotlib
These libraries can be installed using pip by running the following command:

Copy code
pip install tensorflow numpy matplotlib
### Usage
To train the model, run the following command:

Copy code
python train.py
The training data should be stored in a directory named data within the root of the repository. The directory should contain two subdirectories: authentic and forged. The authentic directory should contain authentic images, while the forged directory should contain forged images.

Once the model is trained, you can use it to classify images as authentic or forged using the following command:

php
Copy code
python classify.py <image_path>
Replace <image_path> with the path to the image file you want to classify.

### Contributing
If you find any issues or want to contribute to this repository, feel free to submit a pull request or open an issue.

### License
This repository is licensed under the MIT License. See the LICENSE file for more information.
