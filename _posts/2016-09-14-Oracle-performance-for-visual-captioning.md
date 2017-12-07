---
layout: post
title: "Oracle performance for visual captioning"
date: 2016-09-14 16:55:29
categories: arXiv_CV
tags: arXiv_CV Video_Caption Caption
author: Li Yao, Nicolas Ballas, Kyunghyun Cho, John R. Smith, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
The task of associating images and videos with a natural language description has attracted a great amount of attention recently. Rapid progress has been made in terms of both developing novel algorithms and releasing new datasets. Indeed, the state-of-the-art results on some of the standard datasets have been pushed into the regime where it has become more and more difficult to make significant improvements. Instead of proposing new models, this work investigates the possibility of empirically establishing performance upper bounds on various visual captioning datasets without extra data labelling effort or human evaluation. In particular, it is assumed that visual captioning is decomposed into two steps: from visual inputs to visual concepts, and from visual concepts to natural language descriptions. One would be able to obtain an upper bound when assuming the first step is perfect and only requiring training a conditional language model for the second step. We demonstrate the construction of such bounds on MS-COCO, YouTube2Text and LSMDC (a combination of M-VAD and MPII-MD). Surprisingly, despite of the imperfect process we used for visual concept extraction in the first step and the simplicity of the language model for the second step, we show that current state-of-the-art models fall short when being compared with the learned upper bounds. Furthermore, with such a bound, we quantify several important factors concerning image and video captioning: the number of visual concepts captured by different models, the trade-off between the amount of visual elements captured and their accuracy, and the intrinsic difficulty and blessing of different datasets.

##### Abstract (translated by Google)
将图像和视频与自然语言描述联系起来的任务近来引起了很大的关注。在开发新型算法和发布新数据集方面取得了迅速的进展。事实上，一些标准数据集的最新成果已经被推到了制度上，这个制度越来越难以做出重大的改进。这项工作并没有提出新的模型，而是研究了在不需要额外的数据标注或人工评估的情况下，在各种视觉字幕数据集上实验性地建立性能上限的可能性。特别是，视觉标题被分解为两个步骤：从视觉输入到视觉概念，从视觉概念到自然语言描述。当假定第一步是完美的，并且只需要为第二步训练一个条件语言模型时，就能够获得上限。我们展示了MS-COCO，YouTube2Text和LSMDC（M-VAD和MPII-MD的组合）的构造。令人惊讶的是，尽管我们在第一步中使用了视觉概念提取的不完善的过程，而第二步中使用了简单的语言模型，但是我们发现当与现有的上层模型相比时，界限。此外，在这样一个界限下，我们量化了几个与图像和视频字幕有关的重要因素：不同模型所捕获的视觉概念的数量，所捕获的视觉元素的数量与其准确性之间的折衷，以及不同的数据集。

##### URL
[https://arxiv.org/abs/1511.04590](https://arxiv.org/abs/1511.04590)

##### PDF
[https://arxiv.org/pdf/1511.04590](https://arxiv.org/pdf/1511.04590)

