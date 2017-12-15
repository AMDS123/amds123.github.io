---
layout: post
title: "Deep Predictive Coding Networks for Video Prediction and Unsupervised Learning"
date: 2017-03-01 01:00:54
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Prediction Recognition
author: William Lotter, Gabriel Kreiman, David Cox
mathjax: true
---

* content
{:toc}

##### Abstract
While great strides have been made in using deep learning algorithms to solve supervised learning tasks, the problem of unsupervised learning - leveraging unlabeled examples to learn about the structure of a domain - remains a difficult unsolved challenge. Here, we explore prediction of future frames in a video sequence as an unsupervised learning rule for learning about the structure of the visual world. We describe a predictive neural network ("PredNet") architecture that is inspired by the concept of "predictive coding" from the neuroscience literature. These networks learn to predict future frames in a video sequence, with each layer in the network making local predictions and only forwarding deviations from those predictions to subsequent network layers. We show that these networks are able to robustly learn to predict the movement of synthetic (rendered) objects, and that in doing so, the networks learn internal representations that are useful for decoding latent object parameters (e.g. pose) that support object recognition with fewer training views. We also show that these networks can scale to complex natural image streams (car-mounted camera videos), capturing key aspects of both egocentric movement and the movement of objects in the visual scene, and the representation learned in this setting is useful for estimating the steering angle. Altogether, these results suggest that prediction represents a powerful framework for unsupervised learning, allowing for implicit learning of object and scene structure.

##### Abstract (translated by Google)
在使用深度学习算法解决监督学习任务方面已经取得了长足的进步，但无监督学习的问题 - 利用未标记的例子来了解域的结构 - 仍然是一个难以解决的难题。在这里，我们探索视频序列中未来帧的预测，作为学习有关视觉世界结构的无监督学习规则。我们描述了一个预测神经网络（“PredNet”）的架构，受到来自神经科学文献的“预测编码”概念的启发。这些网络学习预测视频序列中的未来帧，网络中的每个层都进行本地预测，并且只将这些预测的偏差转发给后续网络层。我们表明，这些网络能够强有力地学习预测合成（呈现）对象的运动，并且在这样做的过程中，网络学习内部表示，这对于解码潜在对象参数（例如，姿势）培训意见。我们还表明，这些网络可以扩展到复杂的自然图像流（车载摄像机视频），捕捉自我中心运动和物体在视觉场景中的运动的关键方面，在这种设置中学习的表示对估计转向角度。总之，这些结果表明，预测代表了一个强大的无监督学习框架，允许对象和场景结构的隐式学习。

##### URL
[https://arxiv.org/abs/1605.08104](https://arxiv.org/abs/1605.08104)

##### PDF
[https://arxiv.org/pdf/1605.08104](https://arxiv.org/pdf/1605.08104)

