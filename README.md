# Comparison of Open Neural Network Exchange (ONNX) and TensorFlow Inferences on MobileNetV2

This document provides a comparison of the inference performance of Open Neural Network Exchange (ONNX) and TensorFlow for the MobileNetV2 model. It focuses on key aspects - inference time.

## Introduction to MobileNetV2

MobileNetV2 is a lightweight convolutional neural network architecture designed for mobile and embedded vision applications. It was introduced by Google researchers in the paper "MobileNetV2: Inverted Residuals and Linear Bottlenecks" (2018). MobileNetV2 is known for its efficient use of resources, making it ideal for real-time applications on devices with limited processing power.

## Training
### Machine Configuration
CPU for Colab is an Intel Xeon CPU with 2 vCPUs (virtual CPUs) and 13GB of RAM
## Comparison of ONNX and TensorFlow Inference Time
| Framework  | Inference Time (Mean ± Standard Deviation) |
|------------|---------------------------------------------|
| **TensorFlow** | 0.1977 ± 0.0839                            |
| **ONNX**       | 0.0151 ± 0.0045                            |
