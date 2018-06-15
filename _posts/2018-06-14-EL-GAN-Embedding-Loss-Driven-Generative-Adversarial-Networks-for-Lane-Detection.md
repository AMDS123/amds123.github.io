---
layout: post
title: "EL-GAN: Embedding Loss Driven Generative Adversarial Networks for Lane Detection"
date: 2018-06-14 13:20:20
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN Embedding CNN Semantic_Segmentation Classification Prediction Detection
author: Mohsen Ghafoorian, Cedric Nugteren, N&#xf3;ra Baka, Olaf Booij, Michael Hofmann
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks have been successfully applied to semantic segmentation problems. However, there are many problems that are inherently not pixel-wise classification problems but are frequently formulated as semantic segmentation. This ill-posed formulation consequently necessitates hand-crafted scenario-specific and computationally expensive post-processing methods to convert the per pixel probability maps to final desired outputs. Generative adversarial networks (GANs) can be used to make the semantic segmentation network output to be more realistic or better structure-preserving, decreasing the dependency on potentially complex post-processing. 
 In this work, we propose EL-GAN: a GAN framework to mitigate the discussed problem using an embedding loss. With EL-GAN, we discriminate based on learned embeddings of both the labels and the prediction at the same time. This results in more stable training due to having better discriminative information, benefiting from seeing both 'fake' and 'real' predictions at the same time that substantially stabilizes the adversarial training process. We use the TuSimple lane marking challenge to demonstrate that using our proposed framework it is viable to overcome the inherent anomalies of posing it as a semantic segmentation problem. Not only is the output considerably more similar to the labels when compared to conventional methods, the subsequent post-processing is simpler and crosses the competitive 96% accuracy threshold.

##### Abstract (translated by Google)
卷积神经网络已成功应用于语义分割问题。然而，有许多问题本质上不是像素分类问题，而是经常被表述为语义分割。因此，这种不适合的表述需要手工制作的特定场景和计算上昂贵的后处理方法，以将每像素概率图转换为最终期望的输出。生成对抗网络（GAN）可用于使语义分割网络输出更真实或更好地保留结构，从而降低对潜在复杂后处理的依赖性。
 在这项工作中，我们提出了EL-GAN：一种GAN框架，以减少使用嵌入损失讨论的问题。有了EL-GAN，我们可以根据标签和预测的学习嵌入同时进行区分。由于具有更好的区别性信息，这样可以获得更稳定的培训，因为可以同时看到“假”和“真”预测，从而大大稳定对抗性培训流程。我们使用TuSimple车道标记挑战来证明，使用我们提出的框架，克服将其作为语义分割问题的固有异常是可行的。与传统方法相比，不仅输出更加类似于标签，随后的后处理更简单，并且跨越竞争性的96％准确度阈值。

##### URL
[http://arxiv.org/abs/1806.05525](http://arxiv.org/abs/1806.05525)

##### PDF
[http://arxiv.org/pdf/1806.05525](http://arxiv.org/pdf/1806.05525)

