---
layout: post
title: "DeepBox: Learning Objectness with Convolutional Networks"
date: 2015-09-26 21:38:49
categories: arXiv_CV
tags: arXiv_CV CNN Detection
author: Weicheng Kuo, Bharath Hariharan, Jitendra Malik
mathjax: true
---

* content
{:toc}

##### Abstract
Existing object proposal approaches use primarily bottom-up cues to rank proposals, while we believe that objectness is in fact a high level construct. We argue for a data-driven, semantic approach for ranking object proposals. Our framework, which we call DeepBox, uses convolutional neural networks (CNNs) to rerank proposals from a bottom-up method. We use a novel four-layer CNN architecture that is as good as much larger networks on the task of evaluating objectness while being much faster. We show that DeepBox significantly improves over the bottom-up ranking, achieving the same recall with 500 proposals as achieved by bottom-up methods with 2000. This improvement generalizes to categories the CNN has never seen before and leads to a 4.5-point gain in detection mAP. Our implementation achieves this performance while running at 260 ms per image.

##### Abstract (translated by Google)
现有的对象建议方法主要使用自下而上的提示来排列提议，而我们认为对象实际上是一个高层次的构建。我们主张用数据驱动的语义方法对对象提议进行排序。我们称之为DeepBox的框架使用卷积神经网络（CNN）来重新排列来自自下而上方法的提案。我们使用了一种新颖的四层CNN架构，它与更大的网络一样好，而且速度更快。我们发现DeepBox显着提高了自下而上的排名，实现了与2000年自下而上方法实现的500个提案相同的回忆。这种改进概括为CNN从未见过的类别，并导致4.5分的收益检测mAP。我们的实现在每个图像运行时间为260 ms的情况下实现了这一性能

##### URL
[https://arxiv.org/abs/1505.02146](https://arxiv.org/abs/1505.02146)

##### PDF
[https://arxiv.org/pdf/1505.02146](https://arxiv.org/pdf/1505.02146)

