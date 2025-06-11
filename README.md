# Handwritten Character Recognition Using CNNs and Optimizer Evaluation

## Overview

Handwritten Character Recognition (HCR) is a crucial application in fields such as traffic sign interpretation, document content translation, and textual data extraction. Recent advances in neural networks, particularly Convolutional Neural Networks (CNNs), have significantly improved image classification tasks, including HCR.

This project presents a custom CNN-based approach to recognize English handwritten digits and characters using the popular Kaggle A–Z alphabet dataset. The focus is on evaluating the impact of different optimizers on model performance.

## Key Features

- Utilizes a CNN architecture tailored for handwritten character recognition.
- Evaluates six different optimizers:
  - LAMB
  - Adam
  - Lion
  - RMSprop
  - AdamW
- Experiments with three learning rates for each optimizer:
  - 0.01
  - 0.001
  - 0.0001
- Demonstrates that the LAMB optimizer with a learning rate of 0.001 achieves the best accuracy of 98.27%.

## Dataset

The Kaggle A–Z English Alphabet dataset, containing images of handwritten English letters and digits, serves as the benchmark for training and evaluation.

## Results

The project systematically compares optimizer performance and highlights the superior accuracy and reliability achieved using the LAMB optimizer at the optimal learning rate.

## Usage

1. Clone this repository.
2. Install required dependencies (TensorFlow, NumPy, etc.).
3. Run the training scripts to reproduce experiments.
4. Analyze results and visualizations generated.

## License

This project is for academic and research purposes.

---

Feel free to customize or ask for a more detailed version including installation steps or code examples!
