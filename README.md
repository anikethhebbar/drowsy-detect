
# Driver Drowsiness Detection System
This system enhances road safety by detecting and alerting drivers when they show signs of drowsiness.

## Getting Started
### 1. Clone the Repository

### 2. Model Training
- **CNN**: Run `DDDS_CNN/model_training.py`

### 3. Model Evaluation
Follow the instructions in the notebooks to evaluate the accuracy of both models.

### 4. Using the Models
- **CNN**: Execute `DDDS_CNN/main_capture.py`

## System Overview
The project uses Convolutional Neural Networks (CNN) 

## Prerequisites
Required libraries:
- keras
- cv2
- pygame
- numpy
- matplotlib
- glob
- tqdm

## Data Collection
Datasets are available from specific sources detailed in the repository, with guidelines for accessing and preparing them for training.

## Support and Contributions
Feel free to contribute or raise issues. Check the project documentation for more details.

## License
The project is available under the MIT license, promoting open and free use, modification, and distribution.

## Path Configuration
After cloning the repository, update the following placeholders in the code with your actual file paths:
- `<PATH_TO_TRAIN_DATASET>` and `<PATH_TO_TEST_DATASET>` in `model_training.py` with the paths to your training and testing dataset directories, respectively.
- `<PATH_TO_SAVE_MODEL>` in `training_script.py` with the path where you want to save the trained model.
- `<PATH_TO_ALARM_FILE>`, `<PATH_TO_HAAR_CASCADE>`, and `<PATH_TO_SAVED_MODEL>` in `detection_script.py` with the respective paths to the alarm sound file, Haar cascade XML files, and the saved CNN model.
