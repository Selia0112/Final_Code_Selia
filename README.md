# PHAS0077_Shiyuan_Fang

## Project Overview

This project focuses on analyzing and comparing various deep learning models for detecting and categorizing COVID-19 and other lung-related diseases, such as Viral Pneumonia, from chest X-ray images. The models employed include **EfficientNet**, **InceptionV3**, and **MobileNetV3**, which are known for their robust performance in image classification tasks, especially in medical imaging.

### Models Used:
- **EfficientNet**
- **InceptionV3**
- **MobileNetV3**

These models are trained and evaluated on a medical image dataset to provide insights into the performance of deep learning in medical diagnostics, particularly for COVID-19 detection.

## Data

The dataset used in this project can be downloaded from Kaggle:

[Kaggle COVID-19 Radiography Database](https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database/code)

The dataset contains chest X-ray images classified into four categories: **COVID-19, Viral Pneumonia, Normal,** and **Lung Opacity**. Please download the dataset from the above link before running the project.

## Project Instructions

### Prerequisites

Ensure you have installed the necessary dependencies. The project uses the following Python libraries:

- `TensorFlow`
- `Keras`
- `OpenCV`
- `Matplotlib`
- `Pandas`
- `Numpy`
- `scikit-learn`

You can install the required libraries using:

```bash
pip install -r requirements.txt
```
### Data Preparation

After downloading the dataset from Kaggle, you will need to update the file paths in the code to reflect the location of the images on your local machine. Modify all instances of img_path to point to the correct directory.

For example, replace:
```bash
img_path = "/your/local/path/to/images"
```
with the actual path where your images are stored.

### Running the Code

The code files are structured to be run sequentially, with each notebook handling a specific part of the analysis:

	1.	EfficientNet Model: EfficientNetB0.ipynb
	2.	InceptionV3 Model: InceptionV3.ipynb
	3.	MobileNetV3 Model: MobileNetV3.ipynb

Open each notebook, ensure the img_path is updated to your local dataset path, and run the cells in order. The results for each model will be displayed along with visualizations of the model’s accuracy and loss metrics.

### Results

The performance of each model is evaluated based on:

	•	Accuracy
	•	Precision
	•	Recall
	•	Confusion Matrix

The project also includes visualization techniques such as Grad-CAM to explain the regions of the X-ray images that each model focuses on when making predictions.

### Contact

If you have any questions or issues, feel free to contact the author.
