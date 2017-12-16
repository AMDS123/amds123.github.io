---
layout: post
title: "Learning Inference Models for Computer Vision"
date: 2017-08-31 20:33:06
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge Inference
author: Varun Jampani
mathjax: true
---

* content
{:toc}

##### Abstract
Computer vision can be understood as the ability to perform inference on image data. Breakthroughs in computer vision technology are often marked by advances in inference techniques. This thesis proposes novel inference schemes and demonstrates applications in computer vision. We propose inference techniques for both generative and discriminative vision models. The use of generative models in vision is often hampered by the difficulty of posterior inference. We propose techniques for improving inference in MCMC sampling and message-passing inference. Our inference strategy is to learn separate discriminative models that assist Bayesian inference in a generative model. Experiments on a range of generative models show that the proposed techniques accelerate the inference process and/or converge to better solutions. A main complication in the design of discriminative models is the inclusion of prior knowledge. We concentrate on CNN models and propose a generalization of standard spatial convolutions to bilateral convolutions. We generalize the existing use of bilateral filters and then propose new neural network architectures with learnable bilateral filters, which we call `Bilateral Neural Networks'. Experiments demonstrate the use of the bilateral networks on a wide range of image and video tasks and datasets. In summary, we propose techniques for better inference in several vision models ranging from inverse graphics to freely parameterized neural networks. In generative models, our inference techniques alleviate some of the crucial hurdles in Bayesian posterior inference, paving new ways for the use of model based machine learning in vision. In discriminative CNN models, the proposed filter generalizations aid in the design of new neural network architectures that can handle sparse high-dimensional data as well as provide a way to incorporate prior knowledge into CNNs.

##### Abstract (translated by Google)
计算机视觉可以理解为对图像数据进行推理的能力。计算机视觉技术的突破往往以推理技术的进步为标志。本文提出了新的推理方案，并展示了计算机视觉中的应用。我们提出了生成和辨别视觉模型的推理技术。生成模型在视觉中的使用经常受到后验推理困难的阻碍。我们提出了改进MCMC采样和消息传递推理的推理技术。我们的推理策略是学习单独的判别模型，在生成模型中协助贝叶斯推理。在一系列生成模型上的实验表明，所提出的技术加速了推理过程和/或收敛到更好的解决方案。区分模型设计的一个主要难点是包含了先验知识。我们专注于CNN模型，并提出标准空间卷积推广到双边卷积。我们推广现有的双边滤波器的使用，然后提出新的神经网络架构与可学习的双边滤波器，我们称之为“双边神经网络”。实验证明，在广泛的图像和视频任务和数据集上使用双边网络。总之，我们提出了从逆向图形到自由参数化的神经网络等多种视觉模型的更好的推理技术。在生成模型中，我们的推理技术减轻了贝叶斯后验推理中的一些关键障碍，为在视觉中使用基于模型的机器学习铺平了新的道路。在有区别的CNN模型中，所提出的滤波器概括有助于设计可处理稀疏高维数据的新型神经网络架构，并提供将现有知识并入CNN中的方法。

##### URL
[https://arxiv.org/abs/1709.00069](https://arxiv.org/abs/1709.00069)

##### PDF
[https://arxiv.org/pdf/1709.00069](https://arxiv.org/pdf/1709.00069)

