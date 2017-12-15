---
layout: post
title: "View Synthesis by Appearance Flow"
date: 2017-02-11 20:33:50
categories: arXiv_CV
tags: arXiv_CV CNN Prediction Relation
author: Tinghui Zhou, Shubham Tulsiani, Weilun Sun, Jitendra Malik, Alexei A. Efros
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of novel view synthesis: given an input image, synthesizing new images of the same object or scene observed from arbitrary viewpoints. We approach this as a learning task but, critically, instead of learning to synthesize pixels from scratch, we learn to copy them from the input image. Our approach exploits the observation that the visual appearance of different views of the same instance is highly correlated, and such correlation could be explicitly learned by training a convolutional neural network (CNN) to predict appearance flows -- 2-D coordinate vectors specifying which pixels in the input view could be used to reconstruct the target view. Furthermore, the proposed framework easily generalizes to multiple input views by learning how to optimally combine single-view predictions. We show that for both objects and scenes, our approach is able to synthesize novel views of higher perceptual quality than previous CNN-based techniques.

##### Abstract (translated by Google)
我们解决了新颖视点合成的问题：给定一个输入图像，合成从任意视点观察到的同一物体或场景的新图像。我们将其作为一个学习任务来处理，但关键的是，我们不是从头开始学习像素合成，而是学习从输入图像复制它们。我们的方法利用了这样的观察：同一实例的不同视图的视觉外观是高度相关的，并且可以通过训练卷积神经网络（CNN）来预测外观流而明确地学习这种相关性 - 指定哪个像素在输入视图中可以用来重建目标视图。此外，所提出的框架通过学习如何最优地结合单视图预测而容易地推广到多输入视图。我们表明，对于对象和场景，我们的方法能够合成比以前的基于CNN的技术更高的感知质量的新颖视图。

##### URL
[https://arxiv.org/abs/1605.03557](https://arxiv.org/abs/1605.03557)

##### PDF
[https://arxiv.org/pdf/1605.03557](https://arxiv.org/pdf/1605.03557)

