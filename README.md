# American Sign Language Recognition System

## Overview

This project develops a real-time American Sign Language (ASL) interpreter using deep learning models. The system analyzes video input of ASL signs and converts them into text, aiming to enhance communication and accessibility for deaf and hard-of-hearing individuals.

## Features

- Real-time ASL gesture recognition
- Conversion of ASL signs to text
- Support for 29 classes (26 letters A-Z, SPACE, DELETE, NOTHING)
- High accuracy in gesture classification

## Technology Stack

- Python
- Deep Learning (ResNet-50)
- Computer Vision techniques
- PyTorch
## Dataset

The project uses the American Sign Language (ASL) alphabet dataset:
- 87,000 training images
- 200x200 pixel images
- 29 classes (26 letters, SPACE, DELETE, NOTHING)
- Balanced class distribution

## Methodology

1. **Computer Vision Techniques**
   - Background Subtraction
   - Thresholding and Binary Mask Creation
   - Contour Detection

2. **Deep Learning for Gesture Classification**
   - Transfer Learning with pre-trained ResNet-50
   - Model Fine-tuning
   - Data Preprocessing and Augmentation

## Results

- Training Accuracy: 99.98%
- Final Training Loss: 0.0019

## Future Improvements

- Enhanced data preprocessing and augmentation
- Exploration of transfer learning from larger datasets
- Model architecture modifications
- Implementation of ensemble methods

## Team Members

- Anubhav Garikapadu [ag2112]
- Chandanu Mohan Kalamani [cm1573]
- Hittishi K [hk919]
- Shashwenth M [sm2785]
- Sowmiyanarayan Selvam [ss4370]

## References

1. Ojha, A., Pandey, A., Maurya, S., Thakur, A., & Dayananda, P. (2020). Sign Language to Text and Speech Translation in Real Time Using Convolutional Neural Network. International Journal of Engineering Research & Technology (IJERT), NCAIT - 2020 (Volume 8 - Issue 15).

2. Akano, V. O., & Adejoke. (2018). Conversion of Sign Language To Text And Speech Using Machine Learning Techniques. Journal of Research and Review in Science, 5, 58-65.

3. Sign Language to Text Conversion by @bhaveshsood

## License

[Include your chosen license here]
