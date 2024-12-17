# MultiClass_Object_Detection



Object detection and bounding box regression are crucial in computer vision, especially for detecting and localizing objects in images. Multi-class object detection involves identifying multiple object classes (e.g., airplanes, motorcycles) and predicting their locations using bounding boxes. Bounding box regression refines box coordinates for accurate localization.

Multi-class detectors like R-CNN, Faster R-CNN, YOLO, SSD, and VGG16 utilize convolutional neural networks (CNNs) for predictions. In contrast, single-class object detection focuses only on localization without class differentiation. Unlike single-class models, multi-class detectors require two output branches: one for bounding box regression and another for class prediction.

In this research, we used the Vision Transformer (ViT) with a customized loss function combining IoU and Mean Squared Error (MSE) for bounding box regression. Our model achieves a 95% IoU, outperforming VGG16 and ViT models trained with MSE loss by 5% and 3%, respectively.

Packages versions needed to run this code
Python 3.10
Tensorflow 2.12
Tensorflow-addons==0.21.0

For more details or to cite our work, refer to our [IEEE Publication](https://ieeexplore.ieee.org/document/10685618).
