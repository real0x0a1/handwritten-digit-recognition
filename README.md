# Handwritten Digit Recognition

This project aims to recognize handwritten digits using a neural network trained on the MNIST dataset. Users can draw a digit on the canvas provided by the GUI, and the application will predict the digit using the trained neural network.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Python 3
- tkinter library (for GUI)
- PIL library (for image processing)
- NumPy library
- scipy library

### Installation

1. Clone the repository:

   ```
   git clone https://github.com/real0x0a1/handwritten-digit-recognition.git
   ```

2. Install the required libraries:

   ```
   pip install -r requirements.txt
   ```

### Usage

1. **Train the Model**: 
   First, train the neural network model using the following command:

   ```
   python train.py
   ```

2. **Run the GUI Application**: 
   After training the model, run the GUI application to predict handwritten digits:

   ```
   python gui.py
   ```

3. **Draw and Predict**: 
   Draw a digit on the canvas and click the "Prediction" button to see the predicted digit.

## Project Structure

- `src/`: Contains the source code of the project.
  - `model.py`: Defines the neural network model.
  - `neural_network.py`: Implements the neural network training and cost function calculation.
  - `randInitialise.py`: Contains functions for initializing random weights.
  - `prediction.py`: Implements the digit prediction function.
- `data/`: Contains the MNIST dataset.
- `gui.py`: GUI application for drawing digits and making predictions.
- `train.py`: Script to train the neural network on the MNIST dataset.
- `Theta1.txt` and `Theta2.txt`: Trained weights of the neural network.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## Acknowledgments

- This project is inspired by the famous MNIST dataset.
- Special thanks to contributors and developers of NumPy, scipy, and tkinter libraries.
