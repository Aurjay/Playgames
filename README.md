# Android Rock-Paper-Scissor Classifier using TensorFlow Lite image classification

## Overview

This is an example application for [TensorFlow Lite](https://tensorflow.org/lite)
on Android. It uses
[Image classification](https://www.tensorflow.org/lite/models/image_classification/overview)
to continuously classify whatever it sees from the device's back camera.
Inference is performed using the TensorFlow Lite Java API. The demo app
classifies frames in real-time, displaying the top most probable
classifications. It allows the user to choose between a floating point or
[quantized](https://www.tensorflow.org/lite/performance/post_training_quantization)
model, select the thread count, and decide whether to run on CPU, GPU, or via
[NNAPI](https://developer.android.com/ndk/guides/neuralnetworks).

## Paper Classification :

![rsz_2paper-classified](https://user-images.githubusercontent.com/47591132/112800840-d9d4a880-9078-11eb-9808-2a830f17a643.jpg)

## Rock Classification :

![rock-classified2](https://user-images.githubusercontent.com/47591132/112800887-ebb64b80-9078-11eb-888f-d572fc653548.jpg)

## Scissor Classification : 

![Scissor-classified](https://user-images.githubusercontent.com/47591132/112800990-0b4d7400-9079-11eb-8c63-044e13ab75cb.jpg)
