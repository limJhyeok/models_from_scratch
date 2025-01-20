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
        <th>모델</th>
        <th>Colab</th>
    </tr>
    <tr>
        <td><strong>LeNet</strong><br>Yann LeCun이 제안한 초기 합성곱 신경망 중 하나로, 이미지 분류 작업의 기초를 이루는 모델입니다.</td>
        <td><a href="https://colab.research.google.com/github/limJhyeok/models_from_scratch/blob/main/LeNet.ipynb"><img
                    src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"></a></td>
    </tr>
    <tr>
        <td><strong>VGG Network</strong><br>3x3 합성곱 층을 사용하여 매우 깊은 네트워크를 단순한 구조로 구성한 모델로, 네트워크 깊이가 정확도에 미치는 영향을 탐구합니다.</td>
        <td><a href="https://colab.research.google.com/github/limJhyeok/models_from_scratch/blob/main/VGG.ipynb"><img
                    src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"></a></td>
    </tr>
    <tr>
        <td><strong>GoogLeNet (Inception)</strong><br>효율적인 계산을 위해 <em>Inception 모듈</em>을 도입한 모델로, 파라미터를 줄이면서도 성능을 유지하도록 설계되었습니다.</td>
        <td><a href="https://colab.research.google.com/github/limJhyeok/models_from_scratch/blob/main/GoogLeNet.ipynb"><img
                    src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"></a></td>
    </tr>
    <tr>
        <td><strong>ResNet</strong><br><em>Residual Connection</em> 개념을 도입하여 깊은 네트워크에서 발생하는 기울기 소실 문제를 해결한 모델로, 수백 층의 딥러닝 네트워크를 훈련할 수 있게 했습니다.</td>
        <td><a href="https://colab.research.google.com/github/limJhyeok/models_from_scratch/blob/main/ResNet.ipynb"><img
                    src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"></a></td>
    </tr>
    <tr>
        <td><strong>EfficientNet</strong><br>너비, 깊이, 해상도를 조합하여 효율적으로 확장하는 방법을 도입한 모델로, 효율성과 성능을 모두 달성하며 최신 기술을 선도했습니다.</td>
        <td><a
                href="https://colab.research.google.com/github/limJhyeok/models_from_scratch/blob/main/EfficientNet.ipynb"><img
                    src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"></a></td>
    </tr>
    <tr>
        <td><strong>Transformer</strong><br>순환 신경망(RNN)을 대체하는 <em>Self-Attention</em> 메커니즘을 도입하며 딥러닝에 혁신을 가져온 모델입니다. BERT, GPT와 같은 현대 모델의 핵심입니다.</td>
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
  
