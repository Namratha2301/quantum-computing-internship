# Quantum Convolutional Neural Network for Object Detection and Classification

This project was done in collaboration with IISc Banglore for my capstone project.
<https://arxiv.org/abs/2307.08204>

### Authors:
- Gowri Namratha Meedinti ([gowri.namratha2019@vitstudent.ac.in](mailto:gowri.namratha2019@vitstudent.ac.in))
- Kandukuri Sai Srirekha ([kandukurisai.srirekha2019@vitstudent.ac.in](mailto:kandukurisai.srirekha2019@vitstudent.ac.in))
- Radhakrishnan Delhibabu ([rdelhibabu@vit.ac.in](mailto:rdelhibabu@vit.ac.in))

---

## Overview

This project investigates the use of **Quantum Convolutional Neural Networks (QCNNs)** for object detection and classification. By comparing QCNNs with classical Convolutional Neural Networks (CNNs) and Artificial Neural Networks (ANNs), the study highlights the advantages and limitations of QCNNs in handling complex datasets for image classification tasks.

## Abstract

Quantum Convolutional Neural Networks (QCNNs) leverage quantum computing principles, such as qubits and quantum gates, to process data in a quantum environment. This project explores the potential of QCNNs in comparison to classical models by evaluating performance on accuracy and efficiency metrics. We compare QCNNs with traditional CNNs and ANNs across different conditions, including batch size and input size, using the MNIST dataset for binary classification.

## Keywords

- Quantum Convolutional Neural Network (QCNN)
- Classical Convolutional Neural Network (CNN)
- Artificial Neural Network (ANN)
- Quantum computing
- Machine learning

## Table of Contents

1. [Introduction](#introduction)
2. [Background](#background)
   - [Convolutional Neural Networks (CNN)](#convolutional-neural-networks-cnn)
   - [Quantum Convolutional Neural Networks (QCNN)](#quantum-convolutional-neural-networks-qcnn)
3. [Methodology](#methodology)
   - [Proposed Model](#proposed-model)
4. [Results](#results)
5. [Conclusion](#conclusion)
6. [Future Research Directions](#future-research-directions)

---

## Introduction

This project addresses the increasing computational demand in real-time object detection and classification as datasets grow in complexity. By using qubits, QCNNs can process data in a quantum environment, potentially outperforming traditional neural networks in accuracy and efficiency for certain tasks. 

## Background

### Convolutional Neural Networks (CNN)
CNNs are widely used for image and audio processing due to their ability to detect and learn intricate features. CNNs, however, require high memory and computational resources for large datasets.

### Quantum Convolutional Neural Networks (QCNN)
QCNNs combine quantum computing principles with the CNN architecture. They leverage qubits in a quantum environment to achieve parallelism through superposition, allowing QCNNs to manage complex datasets more effectively.

## Methodology

### Proposed Model
The QCNN model uses a combination of quantum convolutional and pooling layers. The architecture is designed to minimize loss through a quantum optimizer, which adjusts parameters based on the mean squared error (MSE) function. This model is trained and evaluated using the MNIST dataset.

## Results

### Model Comparison

The table below compares the performance of different models on the MNIST dataset for binary classification tasks.

| Model                     | Accuracy | Loss   |
|---------------------------|----------|--------|
| Classical CNN             | 0.999    | 0.0031 |
| Classical NN              | 0.9141   | 0.2180 |
| Quantum Neural Network (QNN) | 0.50-0.60 | 0.22   |
| Quantum Convolutional Neural Network (QCNN) | 0.52-0.61 | 0.54   |

The classical CNN model achieved the highest accuracy, while QCNN models showed promising potential but were limited by current quantum hardware constraints and dataset size.

## Conclusion

Classical CNNs outperform QCNNs on binary classification tasks involving the MNIST dataset, achieving high accuracy and low loss. However, QCNNs show potential for complex, large-scale tasks, where quantum computing’s parallel processing may offer advantages.

## Future Research Directions

Future research can focus on:
- Hybrid models combining classical and quantum networks
- Evaluating QCNNs on unsupervised learning tasks
- Experimenting with larger datasets and improved quantum hardware


