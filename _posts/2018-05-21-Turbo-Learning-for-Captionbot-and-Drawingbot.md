---
layout: post
title: "Turbo Learning for Captionbot and Drawingbot"
date: 2018-05-21 16:43:47
categories: arXiv_CV
tags: arXiv_CV Image_Caption Text_Generation Caption
author: Qiuyuan Huang, Pengchuan Zhang, Dapeng Wu, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
We study in this paper the problems of both image captioning and text-to-image generation, and present a novel turbo learning approach to jointly training an image-to-text generator (a.k.a. captionbot) and a text-to-image generator (a.k.a. drawingbot). The key idea behind the joint training is that image-to-text generation and text-to-image generation as dual problems can form a closed loop to provide informative feedback to each other. Based on such feedback, we introduce a new loss metric by comparing the original input with the output produced by the closed loop. In addition to the old loss metrics used in captionbot and drawingbot, this extra loss metric makes the jointly trained captionbot and drawingbot better than the separately trained captionbot and drawingbot. Furthermore, the turbo-learning approach enables semi-supervised learning since the closed loop can provide peudo-labels for unlabeled samples. Experimental results on the COCO dataset demonstrate that the proposed turbo learning can significantly improve the performance of both captionbot and drawingbot by a large margin.

##### Abstract (translated by Google)
我们在本文中研究了图像字幕和文本到图像生成的问题，并提出了一种新颖的涡轮学习方法来联合训练图像到文本生成器（aka captionbot）和文本到图像生成器（aka drawingbot）。联合训练背后的关键思想是将图像到文本的生成和文本到图像的生成作为对偶问题形成一个闭环，为对方提供信息反馈。基于这样的反馈，我们通过比较原始输入与闭环产生的输出来引入新的损失度量。除了captionbot和drawingbot中使用的旧损失指标外，这种额外的损失指标使得联合训练的captionbot和drawingbot比单独训练的captionbot和drawingbot更好。此外，涡轮学习方法能够实现半监督学习，因为闭环可以为未标记的样本提供peudo标签。 COCO数据集上的实验结果表明，所提出的涡轮学习可以大幅度提高captionbot和drawingbot的性能。

##### URL
[https://arxiv.org/abs/1805.08170](https://arxiv.org/abs/1805.08170)

##### PDF
[https://arxiv.org/pdf/1805.08170](https://arxiv.org/pdf/1805.08170)

