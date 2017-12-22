---
layout: post
title: "Adversarial Synthesis Learning Enables Segmentation Without Target Modality Ground Truth"
date: 2017-12-20 20:22:01
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN Deep_Learning
author: Yuankai Huo, Zhoubing Xu, Shunxing Bao, Albert Assad, Richard G. Abramson, Bennett A. Landman
mathjax: true
---

* content
{:toc}

##### Abstract
A lack of generalizability is one key limitation of deep learning based segmentation. Typically, one manually labels new training images when segmenting organs in different imaging modalities or segmenting abnormal organs from distinct disease cohorts. The manual efforts can be alleviated if one is able to reuse manual labels from one modality (e.g., MRI) to train a segmentation network for a new modality (e.g., CT). Previously, two stage methods have been proposed to use cycle generative adversarial networks (CycleGAN) to synthesize training images for a target modality. Then, these efforts trained a segmentation network independently using synthetic images. However, these two independent stages did not use the complementary information between synthesis and segmentation. Herein, we proposed a novel end-to-end synthesis and segmentation network (EssNet) to achieve the unpaired MRI to CT image synthesis and CT splenomegaly segmentation simultaneously without using manual labels on CT. The end-to-end EssNet achieved significantly higher median Dice similarity coefficient (0.9188) than the two stages strategy (0.8801), and even higher than canonical multi-atlas segmentation (0.9125) and ResNet method (0.9107), which used the CT manual labels.

##### Abstract (translated by Google)
缺乏概括性是基于深度学习的分割的一个关键限制。通常情况下，手动标记新的训练图像分割器官不同的成像模式或分割异常器官不同的疾病队列。如果能够重新使用来自一种模式（例如，MRI）的手动标签来训练用于新模态（例如，CT）的分割网络，则人工努力可以被减轻。以前，已经提出了使用周期生成对抗网络（CycleGAN）来合成目标模态的训练图像的两阶段方法。然后，这些努力使用合成图像独立地训练分割网络。然而，这两个独立的阶段并没有使用综合和分割之间的互补信息。在此，我们提出了一种新的端到端合成和分割网络（EssNet），以实现不成对的MRI到CT图像合成和CT脾肿大分割，而不使用CT上的手工标记。端到端的EssNet实现了比两阶段策略（0.8801）显着更高的中位数Dice相似系数（0.9188），甚至高于使用CT手册的典型多位图分段（0.9125）和ResNet方法（0.9107）标签。

##### URL
[http://arxiv.org/abs/1712.07695](http://arxiv.org/abs/1712.07695)

##### PDF
[http://arxiv.org/pdf/1712.07695](http://arxiv.org/pdf/1712.07695)

