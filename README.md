This repository provides a machine learning workflow for a classification task using Random Forest Classifier and Keras neural network.

### Prerequisites

Make sure you have the following libraries installed:

- pandas
- numpy
- scikit-learn
- tensorflow

### Steps to Replicate the Workflow

1. Clone the repository:
git clone https://github.com/your-username/your-repo.git

2. Navigate to the repository directory:
cd your-repo

3. Install the required libraries (if not already installed):
pip install -r requirements.txt
 
4. Place your dataset in the repository directory. Ensure that it is in CSV format.

5. Update the file path in the `workflow.py` script:
```python
# Membaca dataset
dataset = pd.read_csv('path/to/your/dataset.csv')

6. Run the workflow.py script:
python workflow.py

The script will perform the following steps:

-Read the dataset
-Preprocess the data
-Split the data into training and testing sets
-Train a Random Forest Classifier
-Use the trained Random Forest Classifier to make predictions on the training data
-Define and train a Keras neural network model
-Use the trained Keras model to make predictions on the testing data
-Calculate the accuracy of the predictions
-Save the trained Keras model in H5 format as model.h5
-Convert the Keras model to TensorFlow Lite (TFLite) format
-Save the converted TFLite model as model.tflite
Note: You may need to modify the code in workflow.py to adapt it to your specific dataset and task. Refer to the comments in the script for guidance.
