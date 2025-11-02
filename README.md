# Is_It_a_Bird

**Is_It_a_Bird** is a bird image classification application built as a Jupyter notebook on Kaggle. It's a binary classifier that determines whether an image contains a bird or not. 

This project is part of learning I am doing through a course called **Practical Deep Learning for Coders** at https://course.fast.ai/. My second project [Cloud-Type-Classifier](https://github.com/kristenfoshay/Cloud-Type-Classifier) uses fastai and PyTorch, but this project is my very first experience learning Jupyter notebooks and learning to fine-tune pre-trained models. 

Rather than design it based directly on the project sample in the course which uses fastai, I took a more self-directed approach to help with understanding the methodologies for image classification in more detail. Therefore this project does not use fastai and PyTorch.

## Stack

- **Platform:** Kaggle Notebook (Python environment)
- **Framework:** TensorFlow/Keras for deep learning
- **Libraries:** PIL (image processing), NumPy, Matplotlib, ipywidgets
- **Model:** Convolutional Neural Network (CNN) with dropout layers

## Features

1. Trains on two datasets:
   - Bird species dataset (6 species, 811 images total)
   - Non-bird dataset (Microsoft Common Objects in Context (COCO) dataset)
2. Uses a simple CNN architecture
3. Provides interactive testing: Upload widget and dropdown selector for testing images on trained model
4. Achieves reasonable performance: Final validation accuracy around 6
