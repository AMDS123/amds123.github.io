---
layout: post
title: "A Frequency Domain Neural Network for Fast Image Super-resolution"
date: 2017-12-08 11:53:52
categories: arXiv_CV
tags: arXiv_CV Super_Resolution
author: Junxuan Li, Shaodi You, Antonio Robles-Kelly
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a frequency domain neural network for image super-resolution. The network employs the convolution theorem so as to cast convolutions in the spatial domain as products in the frequency domain. Moreover, the non-linearity in deep nets, often achieved by a rectifier unit, is here cast as a convolution in the frequency domain. This not only yields a network which is very computationally efficient at testing but also one whose parameters can all be learnt accordingly. The network can be trained using back propagation and is devoid of complex numbers due to the use of the Hartley transform as an alternative to the Fourier transform. Moreover, the network is potentially applicable to other problems elsewhere in computer vision and image processing which are often cast in the frequency domain. We show results on super-resolution and compare against alternatives elsewhere in the literature. In our experiments, our network is one to two orders of magnitude faster than the alternatives with an imperceptible loss of performance.

##### Abstract (translated by Google)
在本文中，我们提出了一个图像超分辨率的频域神经网络。网络采用卷积定理，以便在频域中作为乘积投射空间域的卷积。此外，通常由整流器单元实现的深网络中的非线性在这里在频域中被卷积为卷积。这不仅产生一个测试计算效率很高的网络，而且还可以相应地学习一个参数。网络可以使用反向传播进行训练，并且由于使用哈特利变换作为傅里叶变换的替代，所以没有复数。此外，该网络可能适用于计算机视觉和图像处理中经常在频域中投射的其他问题。我们展示超分辨率的结果，并与文献中其他地方的替代方法进行比较。在我们的实验中，我们的网络比性能损失难以察觉的网络要快一到两个数量级。

##### URL
[http://arxiv.org/abs/1712.03037](http://arxiv.org/abs/1712.03037)

##### PDF
[http://arxiv.org/pdf/1712.03037](http://arxiv.org/pdf/1712.03037)

