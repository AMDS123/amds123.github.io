---
layout: post
title: "Wavelet Convolutional Neural Networks for Texture Classification"
date: 2017-07-24 03:59:04
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Shin Fujieda, Kohei Takayama, Toshiya Hachisuka
mathjax: true
---

* content
{:toc}

##### Abstract
Texture classification is an important and challenging problem in many image processing applications. While convolutional neural networks (CNNs) achieved significant successes for image classification, texture classification remains a difficult problem since textures usually do not contain enough information regarding the shape of object. In image processing, texture classification has been traditionally studied well with spectral analyses which exploit repeated structures in many textures. Since CNNs process images as-is in the spatial domain whereas spectral analyses process images in the frequency domain, these models have different characteristics in terms of performance. We propose a novel CNN architecture, wavelet CNNs, which integrates a spectral analysis into CNNs. Our insight is that the pooling layer and the convolution layer can be viewed as a limited form of a spectral analysis. Based on this insight, we generalize both layers to perform a spectral analysis with wavelet transform. Wavelet CNNs allow us to utilize spectral information which is lost in conventional CNNs but useful in texture classification. The experiments demonstrate that our model achieves better accuracy in texture classification than existing models. We also show that our model has significantly fewer parameters than CNNs, making our model easier to train with less memory.

##### Abstract (translated by Google)
纹理分类是许多图像处理应用中的一个重要和挑战性的问题。虽然卷积神经网络（CNNs）在图像分类方面取得了显着的成功，但纹理分类仍然是一个难题，因为纹理通常不包含有关物体形状的足够信息。在图像处理中，纹理分类传统上用频谱分析很好地研究，该分析利用了许多纹理中的重复结构。由于CNN在空间域中原样处理图像，而频谱分析在频域中处理图像，所以这些模型在性能方面具有不同的特征。我们提出了一种新颖的CNN结构，小波CNN，将频谱分析整合到CNN中。我们的见解是，汇聚层和卷积层可以被看作是一种有限的频谱分析形式。基于这种见解，我们将这两个层概括为用小波变换执行谱分析。小波CNN允许我们利用在常规CNN中丢失的光谱信息，但是在纹理分类中是有用的。实验证明，我们的模型在纹理分类上比现有的模型有更好的准确性。我们还表明，我们的模型比CNNs有更少的参数，使得我们的模型更容易训练，内存更少。

##### URL
[https://arxiv.org/abs/1707.07394](https://arxiv.org/abs/1707.07394)

##### PDF
[https://arxiv.org/pdf/1707.07394](https://arxiv.org/pdf/1707.07394)

