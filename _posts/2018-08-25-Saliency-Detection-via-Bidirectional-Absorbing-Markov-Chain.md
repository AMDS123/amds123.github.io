---
layout: post
title: "Saliency Detection via Bidirectional Absorbing Markov Chain"
date: 2018-08-25 09:36:04
categories: arXiv_CV
tags: arXiv_CV Salient Optimization Detection
author: Fengling Jiang, Bin Kong, Ahsan Adeel, Yun Xiao, Amir Hussain
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional saliency detection via Markov chain only considers boundaries nodes. However, in addition to boundaries cues, background prior and foreground prior cues play a complementary role to enhance saliency detection. In this paper, we propose an absorbing Markov chain based saliency detection method considering both boundary information and foreground prior cues. The proposed approach combines both boundaries and foreground prior cues through bidirectional Markov chain. Specifically, the image is first segmented into superpixels and four boundaries nodes (duplicated as virtual nodes) are selected. Subsequently, the absorption time upon transition node's random walk to the absorbing state is calculated to obtain foreground possibility. Simultaneously, foreground prior as the virtual absorbing nodes is used to calculate the absorption time and obtain the background possibility. Finally, two obtained results are fused to obtain the combined saliency map using cost function for further optimization at multi-scale. Experimental results demonstrate the outperformance of our proposed model on 4 benchmark datasets as compared to 17 state-of-the-art methods.

##### Abstract (translated by Google)
通过马尔可夫链的传统显着性检测仅考虑边界节点。然而，除了边界线索之外，背景先验和前景先验线索还起到补充作用以增强显着性检测。在本文中，我们提出了一种考虑边界信息和前景先验线索的基于吸收马尔可夫链的显着性检测方法。所提出的方法通过双向马尔可夫链结合边界和前景先验线索。具体地，首先将图像分割成超像素，并选择四个边界节点（复制为虚拟节点）。随后，计算转变节点随机行走到吸收状态时的吸收时间以获得前景可能性。同时，使用前景作为虚拟吸收节点来计算吸收时间并获得背景可能性。最后，将两个获得的结果融合以使用成本函数获得组合显着图，以进行多尺度的进一步优化。实验结果表明，与17种最先进的方法相比，我们提出的模型在4个基准数据集上的表现优异。

##### URL
[http://arxiv.org/abs/1808.08393](http://arxiv.org/abs/1808.08393)

##### PDF
[http://arxiv.org/pdf/1808.08393](http://arxiv.org/pdf/1808.08393)

