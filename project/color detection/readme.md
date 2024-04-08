## Color Detection Using Deep Learning

## Dataset : https://www.kaggle.com/datasets/adikurniawan/color-dataset-for-color-recognition

## Models -- VGG , ResNet ,EfficientNet

VGG -- 
The VGG (Visual Geometry Group) model is a deep convolutional neural network (CNN) architecture proposed by the Visual Geometry Group at the University of Oxford. It gained prominence for its simplicity and effectiveness in image classification tasks.
The key characteristic of VGG is its deep architecture consisting of a series of convolutional layers followed by max-pooling layers, with a few fully connected layers at the end. It is known for having a uniform architecture with small 3x3 convolutional filters and max-pooling layers with 2x2 filters applied throughout the network. This uniformity makes VGG easy to understand and implement, facilitating its widespread adoption and serving as a baseline for comparison with other CNN architectures.Despite its simplicity, VGG achieved excellent performance on various image recognition benchmarks, demonstrating the power of deep learning architectures for visual tasks. However, due to its depth and high number of parameters, VGG can be computationally expensive and memory-intensive to train and deploy compared to more modern architectures like ResNet or EfficientNet.


ResNet--
ResNet is a deep CNN architecture by Microsoft Research, tackling vanishing gradients with skip connections. Its basic unit, the residual block, includes shortcut connections, aiding gradient flow. Models like ResNet-50 have various depths, offering state-of-the-art performance in image classification. ResNet's skip connections have influenced subsequent architectures, enhancing training efficiency in deep neural networks.


EffiecientNet--
EfficientNet is a deep learning architecture designed to optimize both accuracy and efficiency by scaling the network's depth, width, and resolution simultaneously. Developed by Google researchers, EfficientNet employs a compound scaling method to balance these three dimensions, achieving superior performance with fewer parameters compared to traditional architectures. By scaling the model efficiently, it can adapt to different resource constraints while maintaining high accuracy. EfficientNet has become popular for various computer vision tasks due to its effectiveness in balancing performance and computational cost.
