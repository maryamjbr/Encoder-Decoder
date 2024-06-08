MNIST # Image Reconstruction using Encoder-Decoder Architecture
This project implements an encoder-decoder architecture using PyTorch to reconstruct images from the MNIST dataset. The model is trained to minimize the Mean Squared Error (MSE) between the original and reconstructed images.
## Project Details
The notebook performs the following steps:

- Data Loading and Preprocessing: Loads the MNIST dataset and preprocesses it by converting the images to tensors.
- Model Definition: Defines the Encoder and Decoder classes using convolutional and transposed convolutional layers.
- Training: Trains the encoder-decoder model on the MNIST training data for a specified number of epochs, minimizing the MSE loss.
- Visualization: Visualizes the original and reconstructed images before and after training.
## Results
### Before Training
The original and reconstructed images before training the model are visualized to show the initial state of the model.
### After Training
The original and reconstructed images after training the model for 10 epochs are visualized to show the model's performance in reconstructing the images.