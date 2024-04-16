# Transfer Learning Model Comparison for Animal Classification
This repository contains code for training and evaluating various transfer learning models for the classification of images into four animal classes: elephant, rhino, zebra, and buffalo.

Models Evaluated
# VGG16
Achieved an accuracy of 93%. VGG16 is a popular architecture known for its simplicity and effectiveness.

#ResNet50
Achieved an accuracy of 59%. ResNet50 is a deeper architecture with residual connections, but it showed comparatively lower performance in this task.

#MobileNet
Achieved the highest accuracy of 98%. MobileNet is designed to be lightweight and efficient, making it suitable for mobile and embedded devices.

# EfficientNetB0
Achieved an accuracy of 93%. EfficientNetB0 offers superior performance with scalable architecture.

# DenseNet121
Also achieved an accuracy of 93%. DenseNet121 connects each layer to every other layer, facilitating effective feature reuse.

# Comparative Analysis
MobileNet: Outperformed all other models with the highest accuracy of 98%, indicating its effectiveness in capturing intricate features.

VGG16, EfficientNetB0, and DenseNet121: Achieved the same accuracy of 93%, demonstrating their reliability in the classification task.

ResNet50: Lagged behind with an accuracy of 59%, suggesting potential limitations in its architecture for this specific task.

# Conclusion
While MobileNet demonstrated the highest accuracy, VGG16, EfficientNetB0, and DenseNet121 also performed well in the classification task. The choice of model depends on factors such as computational resources, deployment requirements, and dataset characteristics.
