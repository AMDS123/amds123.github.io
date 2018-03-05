---
layout: post
title: "Deep Unsupervised Intrinsic Image Decomposition by Siamese Training"
date: 2018-03-02 11:06:50
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization Inference Deep_Learning Relation
author: Louis Lettry, Kenneth Vanhoey, Luc van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
We harness modern intrinsic decomposition tools based on deep learning to increase their applicability on realworld use cases. Traditional techniques are derived from the Retinex theory: handmade prior assumptions constrain an optimization to yield a unique solution that is qualitatively satisfying on a limited set of examples. Modern techniques based on supervised deep learning leverage largescale databases that are usually synthetic or sparsely annotated. Decomposition quality on images in the wild is therefore arguable. We propose an end-to-end deep learning solution that can be trained without any ground truth supervision, as this is hard to obtain. Time-lapses form an ubiquitous source of data that (under a scene staticity assumption) capture a constant albedo under varying shading conditions. We exploit this natural relationship to train in an unsupervised siamese manner on image pairs. Yet, the trained network applies to single images at inference time. We present a new dataset to demonstrate our siamese training on, and reach results that compete with the state of the art, despite the unsupervised nature of our training scheme. As evaluation is difficult, we rely on extensive experiments to analyze the strengths and weaknesses of our and related methods.

##### Abstract (translated by Google)
我们利用基于深度学习的现代内部分解工具来增加其在现实世界用例的适用性。传统技术源自Retinex理论：手工制作的先验假设限制了一种优化，以产生一个独特的解决方案，该解决方案在一组有限的示例上得到定性满足。基于监督式深度学习的现代技术利用通常合成或稀疏注释的大规模数据库。因此，野外图像的分解质量是有争议的。我们提出了一个端到端的深度学习解决方案，可以在没有任何地面监控的情况下进行培训，因为这很难获得。时间流逝形成了一个无处不在的数据来源（在场景静态假设下），在不同的阴影条件下捕获一个恒定的反照率。我们利用这种自然的关系在图像对上以无监督的连体方式进行训练。然而，训练好的网络在推理时适用于单幅图像。尽管我们的训练计划无监督，但我们提供了一个新的数据集来展示我们的暹罗训练，并达到与最先进水平相竞争的结果。由于评估很困难，我们依靠大量实验来分析我们及相关方法的优缺点。

##### URL
[http://arxiv.org/abs/1803.00805](http://arxiv.org/abs/1803.00805)

##### PDF
[http://arxiv.org/pdf/1803.00805](http://arxiv.org/pdf/1803.00805)

