# Bangkit Final Project - State Farm Distracted CNN
1. Download the dataset(https://www.kaggle.com/c/state-farm-distracted-driver-detection/data), the process are on the notebook.
2. Create the training and validation batch using the train generator.
3. Create the label by using the train generator function.
4. Training the model.
5. Validating the model.
6. Use the converter to convert the keras model into the tflite model.
7. Move the tflite file and the label into assets label in android folder.
8. Go the FloatMobilenetClassifier and change the path into our previous model and label.

# Distracted Driving Detection 

Distracted driving detection are based on state farm distracted driver dataset, but in this project we preprocess the data by trimming the data.

## Installation

Use pip to install prerequisites on requirements.txt, if you on google colab you can skip this process.

```bash
pip install -r requirements.txt
```

## Usage

Follow the cell on the notebook research file.
```
