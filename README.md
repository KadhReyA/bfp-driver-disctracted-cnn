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

## Datasets
Number of images : 22.424

The 10 classes to predict are:

c0: safe driving

c1: texting - right  

c2: talking on the phone - right

c3: texting - left

c4: talking on the phone - left

c5: operating the radio

c6: drinking

c7: reaching behind

c8: hair and makeup

c9: talking to passenger


## Installation

Use pip to install prerequisites on requirements.txt, if you on google colab you can skip this process.

```bash
pip install -r requirements.txt
```

## Usage

Follow the cell on the notebook research file

## Result

![Graph1](/images/logo.png) ![Graph2](/images/logo.png)

Epoch | Loss | Accuracy | Val_Loss | Val_Accuracy | Total Time | Time / step
------------ | ------------- | ------------ | ------------- | ------------ | ------------- | ----------------
1 | 2.1284 | 0.2590 | 1.7040 | 0.5334 | 111s | 6s/step
2 | 1.4415 | 0.6459 | 1.1622 | 0.7797 | 111s | 6s/step
3 | 0.9861 | 0.8163 | 0.8026 | 0.8748 | 111s | 6s/step
... | ... | ... | ... | ... | ... | ...
6 | 0.3982 | 0.9380 | 0.3560 | 0.9502 | 111s | 6s/step
7 | 0.3256 | 0.9505 | 0.2966 | 0.9545 | 111s | 6s/step
