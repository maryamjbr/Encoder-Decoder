# Image Reconstruction using Encoder-Decoder Architecture
This project implements an encoder-decoder architecture using PyTorch to reconstruct images from the MNIST dataset. The model is trained to minimize the Mean Squared Error (MSE) between the original and reconstructed images.
## Project Details
The notebook performs the following steps:

- Data Loading and Preprocessing: Loads the MNIST dataset and preprocesses it by converting the images to tensors.
- Model Definition: Defines the Encoder and Decoder classes using convolutional and transposed convolutional layers.
- Training: Trains the encoder-decoder model on the MNIST training data for a specified number of epochs, minimizing the MSE loss.
- Visualization: Visualizes the original and reconstructed images before and after training.


## Project Structure

- `Project_03_2.ipynb`: The main Jupyter Notebook containing the implementation of the encoder-decoder model.

## Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/maryamjbr/Encoder-Decoder.git
```

2. Navigate to the project directory:

```bash
cd Encoder-Decoder
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook Project_03_2.ipynb
```

4. Run the cells in the notebook to execute the encoder-decoder model and evaluate its performance.


## Results
- **Loss**: Achieved a training loss of 0.0019.
### Before Training
The original and reconstructed images before training the model are visualized to show the initial state of the model.
![e1](https://github.com/maryamjbr/Encoder-Decoder/assets/135154626/49d2fe91-6505-4e7e-9891-223f41cd77cd)

### After Training
The original and reconstructed images after training the model for 10 epochs are visualized to show the model's performance in reconstructing the images.
![e2](https://github.com/maryamjbr/Encoder-Decoder/assets/135154626/ed3c2617-190e-4402-9155-41f858966d72)
