# Image Classification with CNN Models

This project explores and compares multiple Convolutional Neural Network (CNN) architectures for image classification tasks. The goal is to evaluate how different deep learning models perform on the same dataset and understand the trade-offs between accuracy, complexity, and training efficiency.

## Models Implemented
The following CNN architectures are implemented and evaluated:

- **Basic CNN (BCNN)** – A baseline convolutional neural network
- **VGG16**
- **VGG19**
- **ResNet**

Each model is trained under the same experimental settings to ensure fair comparison.

## Project Structure
├── BCNN/ # Baseline CNN implementation
├── Vgg16/ # VGG16 model
├── Vgg19/ # VGG19 model
├── RestNet/ # ResNet model
├── README.md


## Methodology
- Preprocessing and normalization of image data
- Model training using supervised learning
- Evaluation using classification accuracy and loss
- Performance comparison across different architectures

## Key Findings
- Deeper architectures such as VGG and ResNet generally achieve higher accuracy
- Simpler CNN models train faster but show lower performance
- Model depth and residual connections significantly affect convergence and stability

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

## Motivation
Image classification is a fundamental task in computer vision and serves as the backbone for many applications such as content recommendation, object detection, and visual recognition systems. This project was developed to gain hands-on experience with deep learning architectures and model comparison.

## Future Improvements
- Add data augmentation
- Include more evaluation metrics (precision, recall, confusion matrix)
- Test on larger and more diverse datasets
