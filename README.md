# MNIST Project README

This project contains code for recognizing handwritten digits using the MNIST dataset.

## Dependencies
- Python 3.x
- TensorFlow 2.x
- NumPy

## Directory Structure
- `mnist_project.ipynb`: Jupyter notebook containing the code for the project.
- `data`: Directory containing the MNIST dataset.
- `model`: Directory containing the saved model.

## Usage
1. Download the MNIST dataset and place it in the `data` directory.
2. Run the `mnist_project.ipynb` notebook to train and test the model.

## Model
A Convolutional Neural Network (CNN) model is used for digit recognition. The model's architecture is as follows:
- Convolutional Layer (32 filters, 3x3 kernel, ReLU activation)
- Max Pooling Layer (2x2 pool size)
- Convolutional Layer (64 filters, 3x3 kernel, ReLU activation)
- Max Pooling Layer (2x2 pool size)
- Flatten Layer
- Dense Layer (128 units, ReLU activation)
- Output Layer (10 units, softmax activation)

## Results
The model achieves an accuracy of approximately 98% on the test dataset.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.
