# Keras-Traffic-Sign-Classifier-with-GUI
A Deep Learning-based Traffic Sign Recognition system built using Keras, TensorFlow, and OpenCV with an intuitive graphical user interface (GUI). The application allows users to upload traffic sign images and instantly classify them into predefined traffic sign categories using a Convolutional Neural Network (CNN).

## Overview

Traffic sign recognition is a critical component of Advanced Driver Assistance Systems (ADAS) and autonomous vehicles. This project leverages Convolutional Neural Networks (CNNs) to accurately classify traffic signs from images and provides an easy-to-use desktop GUI for real-time predictions. CNN-based traffic sign classification is a widely adopted approach for autonomous driving and intelligent transportation systems. :contentReference[oaicite:0]{index=0}

This project utilizes keras and tensorflow to train a CNN model to classify images of 43 different traffic signs with relatively high accuracy. 
I achieved a 98% accuracy with this model. 
This repo. also contains the code for a GUI made using tkinter to classify the images. 
And another file wich can be used to use the webcan to detect the traffic signs.
The data set for the project can be found in the following link: https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign 
Unzip the rar file before use before running the code download the following libraries: 

## Features

- Traffic sign image classification using Deep Learning
- CNN model built with Keras and TensorFlow
- User-friendly GUI for image upload and prediction
- Supports multiple traffic sign categories
- Fast inference on local machines
- Image preprocessing and normalization pipeline
- Easy deployment and customization

## Demo

### Workflow

1. Launch the application
2. Upload a traffic sign image
3. Process and preprocess the image
4. Run CNN inference
5. Display predicted traffic sign category

## Model Architecture

The classifier uses a Convolutional Neural Network (CNN) consisting of:

- Convolutional Layers
- ReLU Activation Functions
- Max Pooling Layers
- Fully Connected Layers
- Softmax Classification Layer

CNNs are particularly effective for image classification tasks because they automatically learn spatial features and hierarchical image representations. :contentReference[oaicite:1]{index=1}

## Tech Stack

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Tkinter (GUI)

## Project Structure

```text
Keras-Traffic-Sign-Classifier-with-GUI/
│
├── data/                     # Dataset
├── model/                    # Trained model files
├── gui.py                    # GUI application
├── train.py                  # Model training script
├── predict.py                # Prediction script
├── requirements.txt          # Dependencies
└── README.md
```

## Installation

### Clone Repository

```bash
git clone https://github.com/Melvin-Paul-Jacob/Keras-Traffic-Sign-Classifier-with-GUI.git
cd Keras-Traffic-Sign-Classifier-with-GUI
```

### Create Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate:

**Windows**
```bash
venv\Scripts\activate
```

**Linux/macOS**
```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## Training the Model

Place the dataset in the appropriate directory and run:

```bash
python train.py
```

The training pipeline includes:

- Data loading
- Image preprocessing
- Dataset splitting
- CNN training
- Model evaluation
- Model saving

## Running the GUI

Launch the graphical interface:

```bash
python gui.py
```

### Using the Application

1. Click **Upload Image**
2. Select a traffic sign image
3. Click **Classify**
4. View predicted traffic sign category

The GUI loads the trained Keras model and performs inference on uploaded images, a common deployment approach for traffic sign classifiers. :contentReference[oaicite:2]{index=2}

## Dataset

This project can be trained using traffic sign datasets such as:

- German Traffic Sign Recognition Benchmark (GTSRB)
- Custom traffic sign datasets
- Kaggle traffic sign datasets

Traffic sign datasets typically contain dozens of sign classes and thousands of labeled images for supervised learning. :contentReference[oaicite:3]{index=3}

## Example Classes

Examples of recognizable signs include:

- Stop
- Yield
- Speed Limit
- No Entry
- Turn Left
- Turn Right
- Pedestrian Crossing
- Road Work
- Traffic Signal

## Performance

The trained CNN model is capable of achieving high classification accuracy when trained on sufficiently large traffic sign datasets. Similar Keras-based traffic sign classifiers commonly report accuracies above 95% on benchmark datasets. :contentReference[oaicite:4]{index=4}

## Applications

- Autonomous Vehicles
- Driver Assistance Systems (ADAS)
- Intelligent Transportation Systems
- Traffic Monitoring
- Road Safety Solutions
- Smart Mobility Platforms

## Future Improvements

- Real-time webcam inference
- Video stream classification
- Mobile deployment (Android/iOS)
- Model optimization with TensorRT/ONNX
- Traffic sign detection + classification pipeline
- Support for international traffic sign datasets
- Edge deployment on NVIDIA Jetson devices

## Results

The model successfully classifies traffic sign images through an interactive GUI interface, providing a simple demonstration of Deep Learning-based image classification for transportation applications.

## Author

**Melvin Paul Jacob**

Computer Vision Engineer | AI & Machine Learning Engineer

GitHub:
https://github.com/Melvin-Paul-Jacob

## License

This project is licensed under the MIT License.

---

⭐ If you found this project useful, please consider starring the repository.
