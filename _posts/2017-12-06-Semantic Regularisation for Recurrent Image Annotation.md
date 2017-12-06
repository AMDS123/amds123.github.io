---
layout: post
title: 'Semantic Regularisation for Recurrent Image Annotation'
date: 2017-12-06 08:02:43
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN
author: Feng Liu, Tao Xiang, Timothy M. Hospedales, Wankou Yang, Changyin Sun
---

* content
{:toc}

##### Abstract
The "CNN-RNN" design pattern is increasingly widely applied in a variety of image annotation tasks including multi-label classification and captioning. Existing models use the weakly semantic CNN hidden layer or its transform as the image embedding that provides the interface between the CNN and RNN. This leaves the RNN overstretched with two jobs: predicting the visual concepts and modelling their correlations for generating structured annotation output. Importantly this makes the end-to-end training of the CNN and RNN slow and ineffective due to the difficulty of back propagating gradients through the RNN to train the CNN. We propose a simple modification to the design pattern that makes learning more effective and efficient. Specifically, we propose to use a semantically regularised embedding layer as the interface between the CNN and RNN. Regularising the interface can partially or completely decouple the learning problems, allowing each to be more effectively trained and jointly training much more efficient. Extensive experiments show that state-of-the art performance is achieved on multi-label classification as well as image captioning.

##### Abstract (translated by Google)
“CNN-RNN”设计模式日益广泛应用于各种图像标注任务，包括多标签分类和字幕。现有模型使用弱语义CNN隐藏层或其变换作为图像嵌入，提供CNN和RNN之间的接口。这使RNN在两个工作中过度延伸：预测视觉概念并建模其相关性以生成结构化注释输出。重要的是，这使得CNN和RNN的端到端训练变得缓慢和无效，因为通过RNN向后传播梯度来训练CNN是困难的。我们提出了一个简单的修改设计模式，使学习更有效和高效。具体而言，我们建议使用语义正则化的嵌入层作为CNN和RNN之间的接口。规范界面可以部分或完全解耦学习问题，使每个人都能得到更有效的培训，共同培训更有效率。大量的实验表明，在多标签分类和图像字幕方面实现了最先进的性能。

##### URL
[https://arxiv.org/abs/1611.05490](https://arxiv.org/abs/1611.05490)

