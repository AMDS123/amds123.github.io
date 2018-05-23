---
layout: post
title: "Learning Local Descriptors by Optimizing the Keypoint-Correspondence Criterion: Applications to Face Matching, Learning from Unlabeled Videos and 3D-Shape Retrieval"
date: 2018-05-22 12:07:00
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Nenad Marku&#x161;, Igor S. Pand&#x17e;i&#x107;, J&#xf6;rgen Ahlberg
mathjax: true
---

* content
{:toc}

##### Abstract
Current best local descriptors are learned on a large dataset of matching and non-matching keypoint pairs. However, data of this kind is not always available since detailed keypoint correspondences can be hard to establish. On the other hand, we can often obtain labels for pairs of keypoint bags. For example, keypoint bags extracted from two images of the same object under different views form a matching pair, and keypoint bags extracted from images of different objects form a non-matching pair. On average, matching pairs should contain more corresponding keypoints than non-matching pairs. We describe an end-to-end differentiable architecture that enables the learning of local keypoint descriptors from such weakly-labeled data. Additionally, we discuss how to improve the method by incorporating the procedure of mining hard negatives. We also show how can our approach be used to learn convolutional features from unlabeled video signals and 3D models. 
 Our implementation is available at https://github.com/nenadmarkus/wlrn

##### Abstract (translated by Google)
当前最好的本地描述符是在匹配和非匹配关键点对的大数据集上学习的。然而，这种数据并不总是可用的，因为详细的关键点对应可能难以建立。另一方面，我们通常可以获得成对关键包的标签。例如，从不同视角下的相同物体的两幅图像中提取的关键点袋形成匹配对，并且从不同物体的图像中提取的关键点袋形成不匹配的一对。平均而言，匹配对应包含比不匹配对更多的对应关键点。我们描述了一种端到端的可区分体系结构，可以从这种弱标记数据中学习本地关键点描述符。另外，我们讨论如何通过结合挖掘硬性负面的过程来改进方法。我们还展示了如何使用我们的方法从未标记的视频信号和3D模型中学习卷积特征。
 我们的实施可在https://github.com/nenadmarkus/wlrn上获得

##### URL
[http://arxiv.org/abs/1603.09095](http://arxiv.org/abs/1603.09095)

##### PDF
[http://arxiv.org/pdf/1603.09095](http://arxiv.org/pdf/1603.09095)

