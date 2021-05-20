# AI ML - Human Attributes Detection with Facial Feature Extraction

## Emotion and Gender recognition with Facial feature extraction

This facial attribute extraction program detects facial coordinates using FaceNet model and uses MXNet facial attribute extraction model for extracting 40 types of facial attributes. This solution detects Emotion, Age and Gender along with facial attributes. However in this repository we are only interested in the accuracy results of Gender and Emotion classification. 

Deep Learning Models used for the library are,

- FaceNet model used for facial landmark recognition. (Focus Region)
- GenderNet caffe model used for Gender detection. (Focus Region)
- AgeNet pre-trained caffe model used for Age detection.
- A trained lightened moon Mxnet model used for facial attribute extraction.

## Table of contents

- [Getting started](#getting-started)
- [Features](#features)
- [Emotion Detection Classes](#emotion-detection-classes)
- [Gender Detection Classes](#gender-detection-classes)
- [Usage](#usage)
- [Results](#results)
- [Keywords](#Keywords)

## Getting started

Prerequisites for running the code are:

- Python == 3.6
- python-opencv == 4.2.0
- numpy == 1.18.5
- pandas == 0.24.2
- mxnet == 1.6.0
- python-dotenv == 0.14.0

We have tested our program in above version, however you can use it in other versions as well.

## Features

- Face detection using FaceNet model. (Focus Region)
- Predicts Gender of the detected face.(Focus Region)
- Detects Emotions on the face.(Focus Region)
- Predicts Age of the detected face.
- Detects facial attribute of a face in an image.

    
### Emotion Detection Classes

   - Happy
   - Neutral
   - Surprise
   - Angry
   - Fear
   - Sad

### Gender Detection Classes

   - Male
   - Female

    
## Usage

Inside the project's directory run:

```
python3 predict.py
```
You can find sample images in the Dataset folder and results can be seen on the terminal. Results directory contains images with detected faces.


### Results
#### Original Image

<img src="facial_feature/images/Happy3.jpg" />

#### Detection Results

<img src="facial_feature/results/Happy3.png" />

#### Tiago Simulation Result
<img src="facial_feature/images/ROS_result.jpeg" />

#### NOTE

The pre-trained models aren't available on the repository due to memory constraints

-----

## Credits

- Refered mxnet-face for attribute extraction.  [mxnet-face](https://github.com/tornadomeet/mxnet-face).
- Refered fer2013/IMDB for emotional classification.  [fer2013/IMDB](https://github.com/oarriaga/face_classification).
- Refered AgeGender recognition.  [AgeGender](https://github.com/spmallick/learnopencv/tree/master/AgeGender).


## Keywords

 Mxnet_face, facial_attribute_extraction, Age_recognition, gender_recognition, emotion_recognition, caffemodel, fer2013
