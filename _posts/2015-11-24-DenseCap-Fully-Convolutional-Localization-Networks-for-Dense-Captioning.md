---
layout: post
title: "DenseCap: Fully Convolutional Localization Networks for Dense Captioning"
date: 2015-11-24 05:13:54
categories: arXiv_CV
tags: arXiv_CV Image_Caption Object_Detection Caption CNN Detection
author: Justin Johnson, Andrej Karpathy, Li Fei-Fei
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce the dense captioning task, which requires a computer vision system to both localize and describe salient regions in images in natural language. The dense captioning task generalizes object detection when the descriptions consist of a single word, and Image Captioning when one predicted region covers the full image. To address the localization and description task jointly we propose a Fully Convolutional Localization Network (FCLN) architecture that processes an image with a single, efficient forward pass, requires no external regions proposals, and can be trained end-to-end with a single round of optimization. The architecture is composed of a Convolutional Network, a novel dense localization layer, and Recurrent Neural Network language model that generates the label sequences. We evaluate our network on the Visual Genome dataset, which comprises 94,000 images and 4,100,000 region-grounded captions. We observe both speed and accuracy improvements over baselines based on current state of the art approaches in both generation and retrieval settings.

##### Abstract (translated by Google)
我们介绍密集字幕任务，这需要一个计算机视觉系统来定位和描述自然语言图像中的显着区域。密集字幕任务在描述由单个词组成的情况下将对象检测概括为：当一个预测区域覆盖整个图像时，图像字幕提供。为了共同解决本地化和描述任务，我们提出了一种全卷积本地化网络（FCLN）架构，该架构以单一高效的正向传递来处理图像，不需要外部区域建议，并且可以通过单轮训练来端对端的优化。该体系结构由一个卷积网络，一个新颖的密集定位层和生成标签序列的递归神经网络语言模型组成。我们在Visual Genome数据集上评估我们的网络，其中包含94,000个图像和4,100,000个基于地区的字幕。在生成和检索设置中，我们基于当前最先进的方法观察基线的速度和准确度。

##### URL
[https://arxiv.org/abs/1511.07571](https://arxiv.org/abs/1511.07571)

##### PDF
[https://arxiv.org/pdf/1511.07571](https://arxiv.org/pdf/1511.07571)

