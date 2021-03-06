![Logo](https://storage.googleapis.com/model_garden_artifacts/TF_Model_Garden.png)

# TensorFlow Community Models

This repository provides a curated list of the GitHub repositories with machine learning models and implementations powered by TensorFlow 2.

**Note**: Contributing companies or individuals are responsible for maintaining their repositories.

## Computer Vision

### Image Recognition

| Model | Paper | Features | Maintainer |
|-------|-------|----------|------------|
| [DenseNet 169](https://github.com/IntelAI/models/tree/master/benchmarks/image_recognition/tensorflow/densenet169) | [Densely Connected Convolutional Networks](https://arxiv.org/pdf/1608.06993) | • FP32 Inference | [Intel](https://github.com/IntelAI) |
| [Inception V3](https://github.com/IntelAI/models/tree/master/benchmarks/image_recognition/tensorflow/inceptionv3) | [Rethinking the Inception Architecture<br/>for Computer Vision](https://arxiv.org/pdf/1512.00567.pdf) | • Int8 Inference<br/>• FP32 Inference | [Intel](https://github.com/IntelAI) |
| [Inception V4](https://github.com/IntelAI/models/tree/master/benchmarks/image_recognition/tensorflow/inceptionv4) | [Inception-v4, Inception-ResNet and the Impact<br/>of Residual Connections on Learning](https://arxiv.org/pdf/1602.07261) | • Int8 Inference<br/>• FP32 Inference | [Intel](https://github.com/IntelAI) |
| [MobileNet V1](https://github.com/IntelAI/models/tree/master/benchmarks/image_recognition/tensorflow/mobilenet_v1) | [MobileNets: Efficient Convolutional Neural Networks<br/>for Mobile Vision Applications](https://arxiv.org/pdf/1704.04861) | • Int8 Inference<br/>• FP32 Inference | [Intel](https://github.com/IntelAI) |
| [ResNet 101](https://github.com/IntelAI/models/tree/master/benchmarks/image_recognition/tensorflow/resnet101) | [Deep Residual Learning for Image Recognition](https://arxiv.org/pdf/1512.03385) | • Int8 Inference<br/>• FP32 Inference | [Intel](https://github.com/IntelAI) |
| [ResNet 50](https://github.com/IntelAI/models/tree/master/benchmarks/image_recognition/tensorflow/resnet50) | [Deep Residual Learning for Image Recognition](https://arxiv.org/pdf/1512.03385) | • Int8 Inference<br/>• FP32 Inference | [Intel](https://github.com/IntelAI) |
| [ResNet 50v1.5](https://github.com/IntelAI/models/tree/master/benchmarks/image_recognition/tensorflow/resnet50v1_5) | [Deep Residual Learning for Image Recognition](https://arxiv.org/pdf/1512.03385) | • Int8 Inference<br/>• FP32 Inference<br/>• FP32 Training | [Intel](https://github.com/IntelAI) |

### Segmentation

| Model | Paper | Features | Maintainer |
|-------|-------|----------|------------|
| [Mask R-CNN](https://github.com/NVIDIA/DeepLearningExamples/tree/master/TensorFlow2/Segmentation/MaskRCNN) | [Mask R-CNN](https://arxiv.org/abs/1703.06870) | • Automatic Mixed Precision<br/>• Multi-GPU training support with Horovod<br/>• TensorRT | [NVIDIA](https://github.com/NVIDIA) |
| [U-Net Medical Image Segmentation](https://github.com/NVIDIA/DeepLearningExamples/tree/master/TensorFlow2/Segmentation/UNet_Medical) | [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597) | • Automatic Mixed Precision<br/>• Multi-GPU training support with Horovod<br/>• TensorRT | [NVIDIA](https://github.com/NVIDIA) |

## Contributions

If you want to contribute, please review the [contribution guidelines](https://github.com/tensorflow/models/wiki/How-to-contribute).
