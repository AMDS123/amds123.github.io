---
layout: post
title: "Show-and-Fool: Crafting Adversarial Examples for Neural Image Captioning"
date: 2017-12-06 06:08:59
categories: arXiv_CV
tags: arXiv_CV Image_Caption Adversarial Caption CNN RNN
author: Hongge Chen, Huan Zhang, Pin-Yu Chen, Jinfeng Yi, Cho-Jui Hsieh
mathjax: true
---

* content
{:toc}

##### Abstract
Modern neural image captioning systems typically adopt the encoder-decoder framework consisting of two principal components: a convolutional neural network (CNN) for image feature extraction and a recurrent neural network (RNN) for caption generation. Inspired by the robustness analysis of CNN-based image classifiers to adversarial perturbations, we propose \textbf{Show-and-Fool}, a novel algorithm for crafting adversarial examples in neural image captioning. Unlike image classification tasks with a finite set of class labels, finding visually-similar adversarial examples in an image captioning system is much more challenging since the space of possible captions in a captioning system is almost infinite. In this paper, we design three approaches for crafting adversarial examples in image captioning: (i) targeted caption method; (ii) targeted keyword method; and (iii) untargeted method. We formulate the process of finding adversarial perturbations as optimization problems and design novel loss functions for efficient search. Experimental results on the Show-and-Tell model and MSCOCO data set show that Show-and-Fool can successfully craft visually-similar adversarial examples with randomly targeted captions, and the adversarial examples can be made highly transferable to the Show-Attend-and-Tell model. Consequently, the presence of adversarial examples leads to new robustness implications of neural image captioning. To the best of our knowledge, this is the first work on crafting effective adversarial examples for image captioning tasks.

##### Abstract (translated by Google)
现代的神经图像字幕系统通常采用由两个主要组件组成的编码器 - 解码器框架：用于图像特征提取的卷积神经网络（CNN）和用于字幕生成的递归神经网络（RNN）。受到基于CNN的图像分类器对对抗性干扰的鲁棒性分析的启发，我们提出了一种用于在神经图像字幕中制作对抗性例子的新颖的算法（Show-and-Fool）。与具有有限类别标签的图像分类任务不同，在图像字幕系统中寻找视觉上类似的对抗例子是更具挑战性的，因为字幕系统中的可能字幕的空间几乎是无限的。在本文中，我们设计了三种方法来制作图像字幕中的敌对示例：（i）有针对性的字幕方法; （ii）有针对性的关键字方法;和（iii）没有针对性的方法。我们制定了寻找敌对扰动作为优化问题的过程，并设计了新的有效搜索的损失函数。 Show-and-Tell模型和MSCOCO数据集上的实验结果表明，Show-and-Fool可以成功地制作具有随机目标标题的视觉相似的敌对示例，并且敌对的示例可以高度转移到Show-Attend- - 模型。因此，敌对的例子的存在导致神经图像字幕的新鲁棒性含义。就我们所知，这是第一个为图像字幕任务制定有效的对抗性例子的工作。

##### URL
[http://arxiv.org/abs/1712.02051](http://arxiv.org/abs/1712.02051)

##### PDF
[http://arxiv.org/pdf/1712.02051](http://arxiv.org/pdf/1712.02051)

