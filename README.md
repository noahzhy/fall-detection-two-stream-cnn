# Fall Detection Two Stream CNN
This repository is forked on [vietdzung/fall-detection-two-stream-cnn](https://github.com/vietdzung/fall-detection-two-stream-cnn)

> Real-time fall detection using two-stream convolutional neural net (CNN) with Motion History Image (MHI)
>
> This repository contains code for a real-time fall detection model using two-stream CNN. The optical flow stream is replaced with Motion History Image (MHI) to allow for real-time inference. The utils.py file contains utility code for generating the data, the train_model.py file creates and trains the model, and the fall_detection.py file contains code that runs the model with the weight in the weights folder either on the FDD dataset, a video, or your webcam. More detailed description of the model architecture, performance, as well as demo footage/pictures to come in the near future. Achieved fairly good cross-validated error rate on a subset of data generated. Currently working on acquiring more data and refining data generation technique.

## Test the demo

### First of run it
First of all, make sure that you has been installed follows
* OpenCV ( include OpenCV-contrib )
* Keras
* Numpy ( vision = 1.15 )
* TensorFlow

### Run it
``` shell
python fall_detection,py
```

## Train your own dataset
Firstly, 
