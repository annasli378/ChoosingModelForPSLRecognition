# ChoosingModelForPSLRecognition
Training, evaluating and choosing the best model for sign recognition (signs from Polish Sign Language) 

## Training dataset
Training dataset consists of 29 groups corresponding with choosen letters, numbers and additional signs from PSL. 

Class labels:

Data re-processing consist of:

 - determining 21 hand landmarks using mediapipe library with the minimum detection confidence = 0.7
 - normalization of input data to the range (0, 1)
 - obtaining 42 coordinates (x, y)

## Algorithms

Support Vector Machine

K-nearest neighbors

Random Forest Algorithm

## Results

## Bibliography
