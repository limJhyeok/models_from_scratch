# PyTorch로 딥러닝 모델 직접 구현하기

**언어 선택 / Language Selection:**

- [🇰🇷 한국어 (Korean)](README.ko.md)
- [🇺🇸 English](README.md)

이 리포지토리는 **PyTorch**를 사용하여 다양한 딥러닝의 기초 모델을 직접 구현한 내용을 포함하고 있습니다. 이 프로젝트의 목적은 다음과 같습니다:

1. **PyTorch 숙달**: PyTorch를 활용하여 딥러닝 모델을 처음부터 구현하며 기술을 연마합니다.
2. **핵심 아키텍처 이해**: 현대 딥러닝의 기초를 이루는 CNN(Convolutional Neural Network)과 Transformer 아키텍처에 대한 심도 있는 이해를 목표로 합니다.

## 구현된 모델

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

## 모델 선정 이유
이 모델들은 딥러닝 아키텍처의 발전을 살펴보기에 적합합니다:

- **LeNet**: CNN의 기본 개념을 소개하며 현대 CNN 기반 모델의 시초가 되는 모델입니다.  
- **VGG**와 **GoogLeNet**: 딥러닝 모델을 깊게 쌓았을 때 성능이 향상된다는 직관을 실험적으로 증명했습니다.  
- **ResNet**: 네트워크 깊이가 길어짐에 따른 학습 문제(Vanishing gradient)를 해결합니다.
- **EfficientNet**: 효율적인 딥러닝 모델을 탐구합니다.  
- **Transformer**: 전통적인 CNN과 RNN의 한계를 넘어 어텐션(attention) 메커니즘의 가능성을 보여줍니다.  

## 참고 자료

- PyTorch 공식 문서: [PyTorch Documentation](https://pytorch.org/docs/)
- 원본 논문:
    - [LeNet](http://vision.stanford.edu/cs598_spring07/papers/Lecun98.pdf)
    - [VGG](https://arxiv.org/abs/1409.1556)
    - [GoogLeNet](https://arxiv.org/abs/1409.4842)
    - [ResNet](https://arxiv.org/abs/1512.03385)
    - [EfficientNet](https://arxiv.org/abs/1905.11946)
    - [Transformer](https://arxiv.org/abs/1706.03762)
