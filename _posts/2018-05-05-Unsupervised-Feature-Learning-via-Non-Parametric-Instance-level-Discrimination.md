---
layout: post
title: "Unsupervised Feature Learning via Non-Parametric Instance-level Discrimination"
date: 2018-05-05 00:47:01
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Zhirong Wu, Yuanjun Xiong, Stella Yu, Dahua Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Neural net classifiers trained on data with annotated class labels can also capture apparent visual similarity among categories without being directed to do so. We study whether this observation can be extended beyond the conventional domain of supervised learning: Can we learn a good feature representation that captures apparent similarity among instances, instead of classes, by merely asking the feature to be discriminative of individual instances? We formulate this intuition as a non-parametric classification problem at the instance-level, and use noise-contrastive estimation to tackle the computational challenges imposed by the large number of instance classes. Our experimental results demonstrate that, under unsupervised learning settings, our method surpasses the state-of-the-art on ImageNet classification by a large margin. Our method is also remarkable for consistently improving test performance with more training data and better network architectures. By fine-tuning the learned feature, we further obtain competitive results for semi-supervised learning and object detection tasks. Our non-parametric model is highly compact: With 128 features per image, our method requires only 600MB storage for a million images, enabling fast nearest neighbour retrieval at the run time.

##### Abstract (translated by Google)
对具有注释类标签的数据进行训练的神经网络分类器还可以捕获类别之间的明显的视觉相似性，而不用指示这样做。我们研究这种观察是否可以扩展到传统的监督学习领域之外：我们可以通过仅仅要求特征区分个体实例来学习一个很好的特征表示，该特征表示能够捕获实例之间的明显相似性，而不是类别之间的相似性？我们将此直觉作为实例级的非参数分类问题，并使用噪声对比估计来解决大量实例类带来的计算挑战。我们的实验结果表明，在无监督学习环境下，我们的方法大大超过了ImageNet分类技术的水平。我们的方法同样引人注目，可以通过更多的培训数据和更好的网络架构持续改进测试性能。通过微调学习功能，我们进一步获得半监督学习和物体检测任务的竞争结果。我们的非参数模型非常紧凑：每幅图像有128个特征，我们的方法仅需要600MB存储一百万张图像，从而实现运行时的快速最近邻域检索。

##### URL
[http://arxiv.org/abs/1805.01978](http://arxiv.org/abs/1805.01978)

##### PDF
[http://arxiv.org/pdf/1805.01978](http://arxiv.org/pdf/1805.01978)

