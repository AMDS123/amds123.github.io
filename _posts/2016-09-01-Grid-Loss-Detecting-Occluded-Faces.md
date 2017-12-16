---
layout: post
title: "Grid Loss: Detecting Occluded Faces"
date: 2016-09-01 07:15:13
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face CNN Detection Face_Detection
author: Michael Opitz, Georg Waltner, Georg Poier, Horst Possegger, Horst Bischof
mathjax: true
---

* content
{:toc}

##### Abstract
Detection of partially occluded objects is a challenging computer vision problem. Standard Convolutional Neural Network (CNN) detectors fail if parts of the detection window are occluded, since not every sub-part of the window is discriminative on its own. To address this issue, we propose a novel loss layer for CNNs, named grid loss, which minimizes the error rate on sub-blocks of a convolution layer independently rather than over the whole feature map. This results in parts being more discriminative on their own, enabling the detector to recover if the detection window is partially occluded. By mapping our loss layer back to a regular fully connected layer, no additional computational cost is incurred at runtime compared to standard CNNs. We demonstrate our method for face detection on several public face detection benchmarks and show that our method outperforms regular CNNs, is suitable for realtime applications and achieves state-of-the-art performance.

##### Abstract (translated by Google)
部分遮挡物体的检测是一个具有挑战性的计算机视觉问题。标准卷积神经网络（CNN）检测器在检测窗口的部分被遮挡的情况下失效，因为并不是窗口的每个子部分都是有区别的。为了解决这个问题，我们提出了一种新的CNN损失层，称为网格损失，它独立地将卷积层的子块上的错误率最小化，而不是整个特征图。这导致部件本身具有更强的辨别能力，如果检测窗口部分被遮挡，使检测器恢复。通过将我们的损失层映射回常规的完全连接层，与标准CNN相比，在运行时不会产生额外的计算成本。我们演示了我们在几个公开人脸检测基准上进行人脸检测的方法，并表明我们的方法胜过了常规的CNN，适用于实时应用并实现了最先进的性能。

##### URL
[https://arxiv.org/abs/1609.00129](https://arxiv.org/abs/1609.00129)

##### PDF
[https://arxiv.org/pdf/1609.00129](https://arxiv.org/pdf/1609.00129)

