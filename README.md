# Celeb-DF Deepfake Video Detection Using ResNet

## Overview
This project, focuses on detecting deepfake videos using spatial approaches with ResNet models. Utilizing the Celeb-DF dataset, this research aims to address the challenges posed by deepfakes in digital media, which include misinformation and various forms of manipulation.

## Dataset
The Celeb-DF dataset comprises 590 original videos and 5,639 deepfake videos. This dataset was chosen for its high quality and challenging nature, representing realistic deepfakes found online. For this study, a balanced subset was used for training, validation, and testing to avoid class imbalance.

## Methodology
The project employs ResNet50, a convolutional neural network, optimized for deepfake detection by processing frame-by-frame visual data. A face detection model, FaceNet, is used to crop and preprocess video frames to focus on facial regions. Various data augmentation techniques are applied to enhance model robustness.

## Experiments and Results
Experiments were conducted with different learning rates and schedulers. The best performing model achieved a 93.36% accuracy using a learning rate of 0.001 and a cosine annealing scheduler. This highlights the effectiveness of fine-tuning learning parameters in deepfake detection.

## Conclusion
The study demonstrates the capability of convolutional neural networks, specifically ResNet50, to detect deepfake videos with high accuracy. This contributes significantly to ongoing efforts in digital media integrity and misinformation combat.

## References
1. He, K., Zhang, X., Ren, S., & Sun, J. (2015). Deep Residual Learning for Image Recognition. arXiv:1512.03385.
2. Kingma, D. P., & Ba, J. (2014). Adam: A method for stochastic optimization. arXiv:1412.6980.
3. Schroff, F., Kalenichenko, D., & Philbin, J. (2015). FaceNet: A unified embedding for face recognition and clustering. IEEE CVPR.
4. Li, Y., & Lyu, S. (2020). Celeb-DF: A Large-scale Challenging Dataset for DeepFake Forensics. IEEE CVPR.
