# Deep Learning Models from scratch with PyTorch

This repository contains implementations of various foundational deep learning models using **PyTorch**. The purpose of this project is twofold:

1. **Master PyTorch:** Develop and refine skills in building deep learning models from scratch using PyTorch.
2. **Understand Core Architectures:** Gain an in-depth understanding of CNN (Convolutional Neural Network) and Transformer architectures, which form the foundation of modern deep learning.

## Implemented Models
<table>
    <tr>
        <th>Model</th>
        <th>Colab</th>
    </tr>
    <tr>
        <td><strong>LeNet</strong><br>One of the earliest convolutional neural networks introduced by Yann LeCun. 
          A foundational model for image classification tasks.</td>
        <td><a href="https://colab.research.google.com/github/limJhyeok/models_from_scratch/blob/main/LeNet.ipynb"><img
                    src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"></a></td>
    </tr>
    <tr>
        <td><strong>VGG Network</strong><br>Known for its simplicity and use of very deep networks composed of 3x3
            convolution layers. Explores the role of network depth in improving accuracy.</td>
        <td><a href="https://colab.research.google.com/github/limJhyeok/models_from_scratch/blob/main/VGG.ipynb"><img
                    src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"></a></td>
    </tr>
    <tr>
        <td><strong>GoogLeNet (Inception)</strong><br>Introduced the <em>Inception module</em>, allowing for efficient
            computation with reduced parameters. Demonstrates the importance of designing models with computational
            efficiency in mind.</td>
        <td><a href="https://colab.research.google.com/github/limJhyeok/models_from_scratch/blob/main/GoogLeNet.ipynb"><img
                    src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"></a></td>
    </tr>
    <tr>
        <td><strong>ResNet</strong><br>Introduced the concept of <em>residual connections</em>, addressing the vanishing
            gradient problem in deep networks. Paved the way for very deep architectures with hundreds of layers.</td>
        <td><a href="https://colab.research.google.com/github/limJhyeok/models_from_scratch/blob/main/ResNet.ipynb"><img
                    src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"></a></td>
    </tr>
    <tr>
        <td><strong>EfficientNet</strong><br>Scales models effectively across width, depth, and resolution using a
            compound scaling method. Combines efficiency and performance, achieving state-of-the-art results.</td>
        <td><a
                href="https://colab.research.google.com/github/limJhyeok/models_from_scratch/blob/main/EfficientNet.ipynb"><img
                    src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"></a></td>
    </tr>
    <tr>
        <td><strong>Transformer</strong><br>Revolutionized deep learning by replacing RNNs with self-attention
            mechanisms. Forms the backbone of many modern models like BERT and GPT.</td>
        <td><a
                href="https://colab.research.google.com/github/limJhyeok/models_from_scratch/blob/main/Transformer.ipynb"><img
                    src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"></a></td>
    </tr>
</table>

## Why These Models?

These models were selected to cover the evolution of deep learning architectures:

- **LeNet** introduces CNN basics.
- **VGG** and **GoogLeNet** explore architectural innovations for improving depth and efficiency.
- **ResNet** solves the challenges of training very deep networks.
- **EfficientNet** optimizes model scaling.
- **Transformer** breaks away from traditional CNNs and RNNs, showcasing the versatility of attention mechanisms.

## Resources

- PyTorch Official Documentation: https://pytorch.org/docs/
- Original Papers:
    - [LeNet](http://vision.stanford.edu/cs598_spring07/papers/Lecun98.pdf)
    - [VGG](https://arxiv.org/abs/1409.1556)
    - [GoogLeNet](https://arxiv.org/abs/1409.4842)
    - [ResNet](https://arxiv.org/abs/1512.03385)
    - [EfficientNet](https://arxiv.org/abs/1905.11946)
    - [Transformer)(https://arxiv.org/abs/1706.03762)
