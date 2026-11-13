# PyTorch Deep Learning Notebooks

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-EE4C2C?logo=pytorch&logoColor=white)](https://pytorch.org/)
[![Jupyter](https://img.shields.io/badge/Notebooks-Jupyter-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)

A hands-on introduction to deep learning with PyTorch. These notebooks cover the core workflow from preparing data and defining a model to training, evaluation, and visualization through examples in image classification, sequence modeling, and transfer learning.

## Notebooks

| Topic | Example |
| --- | --- |
| **ANN** | Handwritten digit classification with MNIST — [`01-ANN/ANN_Digit_Classification.ipynb`](01-ANN/ANN_Digit_Classification.ipynb) |
| **CNN** | Image classification with CIFAR-10 — [`02-CNN/cnn.ipynb`](02-CNN/cnn.ipynb) |
| **RNN** | Sine-wave sequence prediction — [`03-RNN/rnn.ipynb`](03-RNN/rnn.ipynb) |
| **LSTM** | Next-word prediction with a sample product review — [`04-LSTM/lstm.ipynb`](04-LSTM/lstm.ipynb) |
| **Transfer Learning** | Flower classification with pretrained MobileNetV2 and Oxford Flowers 102 — [`05-Transfer-Learning/transfer_learning.ipynb`](05-Transfer-Learning/transfer_learning.ipynb) |

## What You'll Learn

- Build, train, and evaluate neural networks with PyTorch.
- Prepare and visualize image and sequential data.
- Explore CNNs, RNNs, and LSTMs through practical examples.
- Adapt a pretrained model to a new image-classification task.

## Getting Started

Open a notebook in Jupyter Notebook, JupyterLab, or Google Colab and run its cells in order. To run the notebooks locally, install Python 3 and the required packages:

```bash
python -m pip install torch torchvision numpy matplotlib scikit-learn seaborn tqdm jupyter
```

The notebooks download datasets and pretrained weights when needed. A CUDA-capable GPU is optional; the examples use a GPU when available and otherwise run on CPU. For GPU setup, see the [official PyTorch installation guide](https://pytorch.org/get-started/locally/).

## Suggested Learning Path

ANN → CNN → RNN → LSTM → Transfer Learning

## Notes

These notebooks are educational examples. Training time and results may vary depending on hardware, package versions, and notebook settings.
