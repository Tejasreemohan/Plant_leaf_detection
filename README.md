# Plant Leaf Disease Detection

This project aims to identify and classify diseases in plant leaves using image processing and deep learning techniques. The system leverages a dataset of leaf images to accurately detect diseases at an early stage, providing a scalable and cost-effective solution for agricultural monitoring.

## Table of Contents
- [Introduction](#introduction)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Training](#model-training)
- [Results](#results)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## Introduction
Early detection of plant leaf diseases is crucial for timely intervention and treatment, which can significantly improve crop yield and quality. This project utilizes convolutional neural networks (CNNs) to automatically classify plant leaf diseases from images, reducing the need for manual inspection.

## Tech Stack
- Programming Language: Python
- Image Processing: OpenCV
- Deep Learning Frameworks: TensorFlow, Keras
- Data Manipulation: Pandas, NumPy
- Visualization: Matplotlib, Seaborn
- Model Evaluation: Sklearn
- Development Environment: Jupyter Notebook
## Installation

1. Clone the repository:

```bash
git clone https://github.com/Tejasreemohan/Plant_leaf_detection.git
cd Plant_leaf_detection
 ```

2. Create a virtual environment and activate it:
```bash
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
 ```

3. Install the required packages:
```bash
pip install -r requirements.txt
 ```


## Usage
Prepare your dataset and place it in the data/ directory.
Preprocess the images and labels using the provided scripts.
Train the model using the training script.
Use the trained model to make predictions on new images.

## Dataset
The dataset should consist of images of plant leaves categorized into different disease classes.

https://www.kaggle.com/datasets/emmarex/plantdisease

## Model Training

Train the model using the provided Jupyter notebooks or Python scripts. Ensure that the data is preprocessed and split into training and validation sets.

## Results

The trained model achieves high accuracy in detecting plant leaf diseases. Visualization tools like Matplotlib and Seaborn can be used to analyze performance.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## Acknowledgements
Open-source libraries used in this project
Dataset providers from Kaggle
