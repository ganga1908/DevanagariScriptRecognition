# Devanagari Script Recognition

> Detect Devanagari script as gestured by the user

## Modules used
 - OpenCV
 - NumPy
 - Pandas
 - Keras; Tensorflow

## Implementation
 1. `train.py` trains the CNN model using relu activation function
 2. `application.py` performs detection on real-time input
 
## Points to note
 - 46 classes; 36 letters and 10 digits
 - Number of training samples: 70000
 - Number of test samples: 2000
 - Trained over 8 epochs
 - Batch size: 64
 - Colour range to be taken into account for pointer
 
*`data.csv` gives the CSV version of folders `Train` and `Test`* 

*Observe the values for different parameters*

**Train accuracy -** 98.41%

**Test accuracy -**  96.85%

**CNN error -** 3.15%