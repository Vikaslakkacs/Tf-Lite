# Tf Lite
Tensorflow models are ran in Computers or cloud because of it high computational power and huge data requirement.
But when you want to run the same tensorflow models in edge devices such as mobile Phone or Raspberry Pi etc., is not possible because of its limited memory and more power consumption.
Tensorflow models size varies from Hundreds of MB to GBs of data. When you copy those models and try to run it in mobile devices, Well it crashes your phone and running it on Raspberry Pi is impossible.
To overcome this difficulty, Tensorflow has introduces a lighter version of Tensorflow which is Tensorflow Lite (Tf-Lite). Tensorflow lite allows users to run on Edge devices even on Micro controllers. Its smaller binary size and  low latency enables to perform tasks on edge devices.
## There are two components in tensorflow:
1. Tensorflow converter: This component converts Tensorflow model to Tensorflow lite models with the reduction of size. It uses several type of quatization methods to convert a tf model to several types of tflite models, which we work on.
2. Tensorflow interpreter: This will help us to run tf lite models on the hardwares of edge devices. We can run Tflite model on local computers with the use of Tensorflow Python interpreter.

## Steps We Follow in the process of conversion:
1. We Pick a model (Either Pre-trained or we can create a model of our own)
2. Save the model
3. Convert the model to tflite
4. Deploy the model

## Below are some useful links:
https://www.tensorflow.org/lite/guide

