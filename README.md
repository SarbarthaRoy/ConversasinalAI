# OCR-Digit-Recognition-System
Installation

## Clone the repository:
git clone https://github.com/SarbarthaRoy/OCR-Digit-Recognition-System.git

## Install the required dependencies by running:

pip install -r requirements.txt

Run the code by :
python DIGIT RECOGNITION.py

## Usage
The DIGIT RECOGNITION.py script loads the MNIST dataset, preprocesses the images, defines a sequential neural network model, trains the model, evaluates its performance, and displays predictions for a subset of test images.

## Configuration
You can modify the code to experiment with different configurations:

Adjust the number of epochs for training by modifying epochs in the model.fit function call.
Change the architecture of the model by adding, removing, or modifying layers in the model = keras.models.Sequential([...]) block.
Explore different activation functions or optimizer algorithms by modifying the respective parameters in the model.compile function call.

## Results
The code outputs the test accuracy of the trained model and visualizes predictions for a subset of test images. It helps to assess the model's performance and observe its predictions alongside the true labels.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License.

## Acknowledgments
The code is based on the TensorFlow and Keras documentation and examples.
The MNIST dataset is a popular benchmark for image classification tasks.
Feel free to customize the README file according to your specific project requirements, adding additional sections or information as needed.
