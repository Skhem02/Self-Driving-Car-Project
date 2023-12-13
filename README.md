# Self-Driving Car Project

This project is a self-driving car simulation using a convolutional neural network (CNN) implemented in TensorFlow. The model predicts the steering angle based on input images from a driving dataset.

## Getting Started

### Prerequisites

- Python 3.x
- TensorFlow (compatible with v1)
- OpenCV
- NumPy

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/self-driving-car-project.git
   cd self-driving-car-project
### Dataset
- The driving dataset used in this project can be downloaded from the following link:

  [Datasets](https://drive.google.com/file/d/1Ue4XohCOV5YXy57S_5tDfCVqzLr101M7/view?usp=drivesdk)https://drive.google.com/file/d/1Ue4XohCOV5YXy57S_5tDfCVqzLr101M7/view?usp=drivesdk)
  
## Usage
### Training the Model:

- Run the train.py script to train the self-driving car model.

- bash

      python train.py
- The training script will save model checkpoints and TensorBoard logs in the ./save and ./logs directories.

### Running the Simulation:

#### After training, run the run_dataset.py script to simulate the self-driving car using images from the dataset.

- bash

      python run_dataset.py

- Press 'q' to exit the simulation.

### Real-time Prediction:

- Use the run.py script to make real-time predictions using a connected camera.

- bash 

      python run.py

## Project Structure

- driving_dataset/: Contains the driving dataset.
- model.py: Defines the neural network model.
- train.py: Script for training the model.
- run_dataset.py: Script for simulating the self-driving car using the dataset.
- run.py: Script for real-time prediction using a camera.
- steering_wheel_image.jpg: Image of a steering wheel for visualization.

## License

- This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- This project is based on the Autopilot-TensorFlow project by SullyChen. See License.txt for its license.
- The model architecture is inspired by the NVIDIA End-to-End Self-Driving Car model. Refer to the NVIDIA Paper for more details.
- Thanks to the open-source community for various libraries used in this project.
