
# Cotton Disease Detection using ResNet50

This project implements a deep learning model based on the ResNet50 architecture for detecting diseases in cotton plants. The code utilizes TensorFlow 2.9.1 for model development and evaluation.

## Installation

To run the code, you need to install TensorFlow version 2.9.1. You can install it using pip:

```bash
!pip install tensorflow==2.9.1
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/keshav-kumar-01/Cotton-Plant-Disease-Resnet50.git
```

2. Install the required dependencies:

```bash
# Assuming you are using a virtual environment
pip install -r requirements.txt
```

3. Run the provided Python script:

```bash
python cotton_disease_detection.py
```

## Steps in the Notebook

1. Importing Libraries and Setting Up Environment
2. Mounting Google Drive to Access Files
3. Setting Up Kaggle Credentials and Downloading Dataset
4. Preprocessing and Configuring GPU Options
5. Loading Pre-trained ResNet50 Model
6. Freezing Layers in the Base Model
7. Adding Fully Connected Layers
8. Compiling the Model
9. Training the Model
10. Evaluating the Model Using Confusion Matrix
11. Plotting Training Metrics (Loss and Accuracy)
12. Saving the Model as an H5 File

Feel free to modify the installation and usage instructions based on your specific setup and preferences.
```

This README provides a guide on how to install dependencies, use the provided code, and understand the steps involved in the notebook. Adjustments can be made as needed for your environment and requirements.
