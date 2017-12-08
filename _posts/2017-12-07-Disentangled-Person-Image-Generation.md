---
layout: post
title: "Disentangled Person Image Generation"
date: 2017-12-07 14:03:12
categories: arXiv_CV
tags: arXiv_CV Re-identification Adversarial Person_Re-identification Embedding
author: Liqian Ma, Qianru Sun, Stamatios Georgoulis, Luc Van Gool, Bernt Schiele, Mario Fritz
mathjax: true
---

* content
{:toc}

##### Abstract
Generating novel, yet realistic, images of persons is a challenging task due to the complex interplay between the different image factors, such as the foreground, background and pose information. In this work, we aim at generating such images based on a novel, two-stage reconstruction pipeline that learns a disentangled representation of the aforementioned image factors and generates novel person images at the same time. First, a multi-branched reconstruction network is proposed to disentangle and encode the three factors into embedding features, which are then combined to re-compose the input image itself. Second, three corresponding mapping functions are learned in an adversarial manner in order to map Gaussian noise to the learned embedding feature space, for each factor respectively. Using the proposed framework, we can manipulate the foreground, background and pose of the input image, and also sample new embedding features to generate such targeted manipulations, that provide more control over the generation process. Experiments on Market-1501 and Deepfashion datasets show that our model does not only generate realistic person images with new foregrounds, backgrounds and poses, but also manipulates the generated factors and interpolates the in-between states. Another set of experiments on Market-1501 shows that our model can also be beneficial for the person re-identification task.

##### Abstract (translated by Google)
由于前景，背景和姿势信息等不同图像因素之间的复杂相互作用，生成新颖而逼真的人物图像是一项具有挑战性的任务。在这项工作中，我们的目标是基于一个新颖的两阶段重建流水线来生成这样的图像，该流水线学习上述图像因子的解开表示，并且同时生成新的人物图像。首先提出了一种多分支重建网络，将三个因素分解并嵌入到特征中，然后将其组合成输入图像本身。其次，为了将高斯噪声分别映射到所学习的嵌入特征空间，针对每个因子分别以对抗方式学习三个对应的映射函数。使用所提出的框架，我们可以操纵输入图像的前景，背景和姿态，还可以对新的嵌入特征进行采样以产生这样的目标操作，从而提供对生成过程的更多控制。 Market-1501和Deepfashion数据集上的实验表明，我们的模型不仅能生成具有新的前景，背景和姿势的真实人物图像，还能处理生成的因素并插入中间状态。 Market-1501的另一组实验表明，我们的模型也可以有利于人重新识别任务。

##### URL
[http://arxiv.org/abs/1712.02621](http://arxiv.org/abs/1712.02621)

##### PDF
[http://arxiv.org/pdf/1712.02621](http://arxiv.org/pdf/1712.02621)

