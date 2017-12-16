---
layout: post
title: "NormFace: L2 Hypersphere Embedding for Face Verification"
date: 2017-07-26 17:58:43
categories: arXiv_CV
tags: arXiv_CV Face Embedding CNN
author: Feng Wang, Xiang Xiang, Jian Cheng, Alan L. Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Thanks to the recent developments of Convolutional Neural Networks, the performance of face verification methods has increased rapidly. In a typical face verification method, feature normalization is a critical step for boosting performance. This motivates us to introduce and study the effect of normalization during training. But we find this is non-trivial, despite normalization being differentiable. We identify and study four issues related to normalization through mathematical analysis, which yields understanding and helps with parameter settings. Based on this analysis we propose two strategies for training using normalized features. The first is a modification of softmax loss, which optimizes cosine similarity instead of inner-product. The second is a reformulation of metric learning by introducing an agent vector for each class. We show that both strategies, and small variants, consistently improve performance by between 0.2% to 0.4% on the LFW dataset based on two models. This is significant because the performance of the two models on LFW dataset is close to saturation at over 98%. Codes and models are released on this https URL

##### Abstract (translated by Google)
由于卷积神经网络的最新发展，人脸验证方法的性能迅速提高。在典型的人脸验证方法中，特征归一化是提高性能的关键步骤。这激励我们在培训过程中引入和研究正常化的效果。但我们认为这是不平凡的，尽管正常化是可以区分的。我们通过数学分析来识别和研究与正常化相关的四个问题，从而产生理解并帮助进行参数设置。基于这个分析，我们提出了两种使用归一化特征的训练策略。首先是softmax损失的修改，它优化余弦相似性而不是内积。第二个是通过为每个类引入一个代理向量来重新进行度量学习。我们表明，基于两个模型的LFW数据集中，两种策略和小型变体的性能持续提高了0.2％到0.4％之间。这是重要的，因为LFW数据集上的两个模型的性能接近98％以上饱和。代码和模型在这个https URL上发布

##### URL
[https://arxiv.org/abs/1704.06369](https://arxiv.org/abs/1704.06369)

##### PDF
[https://arxiv.org/pdf/1704.06369](https://arxiv.org/pdf/1704.06369)

