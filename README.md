# Stress Detection Using Machine Learning

## Project Description
This project aims to detect stress levels using machine learning techniques. It involves data preprocessing, feature extraction, and model training to classify stress levels from given input data.

## Installation

### Clone the Repository
```bash
git clone https://github.com/srishti2207/Stress-Detection-Using-DL-techniques.git
cd Stress-Detection-Using-DL-techniques
```

### Install Dependencies
Ensure you have all the necessary libraries installed. You can install them using:
```bash
pip install -r requirements.txt
```

### Google Drive Setup (if using Google Colab)
To run the notebook in Google Colab, you must mount your Google Drive and update the path to the dataset.
```python
from google.colab import drive
drive.mount('/content/drive')

# Update the path to your dataset
DRIVE_PATH = '/content/drive/MyDrive/CIS_583_DL'
```

## Usage

1. **Load the Data**
   Ensure your dataset (`all_clean_data.csv`) is uploaded to your Google Drive (if using Colab).

2. **Run the Notebook**
   Execute the cells in the notebook sequentially. The notebook is divided into the following sections:
   - Imports & Helper Functions
   - Data Loading & Preprocessing
   - Feature Extraction
   - Model Training
   - Model Evaluation

## Dependencies
The project requires the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- keras
- scikit-learn
- tensorflow

You can install the required packages using:
```bash
pip install pandas numpy matplotlib seaborn keras scikit-learn tensorflow
```

## Dataset Information
The dataset should be placed in the specified path in your Google Drive if using Colab. It contains the features necessary for training and testing the models.

## Model Information
The project uses several machine learning models to detect stress levels, including:
- Random Forest Classifier
- Logistic Regression
- Multinomial Naive Bayes
- Deep Learning models with TensorFlow/Keras

## Results
The results of the model evaluations, including accuracy, precision, recall, and confusion matrices, are displayed in the notebook.

## Contributing
If you wish to contribute to this project, please fork the repository and submit a pull request.

## Contact Information
For any inquiries or issues, please contact at srishtik@umich.edu.
