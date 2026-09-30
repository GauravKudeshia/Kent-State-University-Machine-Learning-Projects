# Computer Vision: Cats vs. Dogs with CNN and VGG16

**Advanced Machine Learning — Assignment 2**  
**Group:** Gaurav Kudeshia and Anurodh Singh

## Project objective
Build and evaluate convolutional neural networks for binary image classification using the Cats vs. Dogs dataset, comparing models trained from scratch with pretrained transfer-learning approaches.

## Methods
- Convolutional Neural Networks (CNNs)
- Data augmentation
- Dropout regularization
- VGG16 pretrained on ImageNet
- Feature extraction and fine-tuning
- Training/validation/test evaluation

## Selected results from the project report
| Approach | Validation Accuracy | Test Accuracy |
|---|---:|---:|
| Sample training (1,000) | 0.739 | 0.723 |
| Data augmentation + dropout (2,870) | 0.821 | 0.806 |
| VGG16 fine-tuning (1,000) | 0.979 | 0.974 |
| VGG16 fine-tuning (5,000) | 0.958 | 0.970 |
| VGG16 fine-tuning (10,000) | 0.960 | 0.9575 |

## Skills demonstrated
Computer vision, transfer learning, deep learning model evaluation, regularization, overfitting mitigation, TensorFlow/Keras, and experimental comparison.

## Repository note
The notebook in this folder is a clean GitHub copy of the original coursework notebook. Large execution outputs were removed for readability; the project code and markdown cells were retained.
