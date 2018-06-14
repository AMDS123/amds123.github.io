---
layout: post
title: "Improving Cytoarchitectonic Segmentation of Human Brain Areas with Self-supervised Siamese Networks"
date: 2018-06-13 15:17:27
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Detection
author: Hannah Spitzer, Kai Kiwitz, Katrin Amunts, Stefan Harmeling, Timo Dickscheid
mathjax: true
---

* content
{:toc}

##### Abstract
Cytoarchitectonic parcellations of the human brain serve as anatomical references in multimodal atlas frameworks. They are based on analysis of cell-body stained histological sections and the identification of borders between brain areas. The de-facto standard involves a semi-automatic, reproducible border detection, but does not scale with high-throughput imaging in large series of sections at microscopical resolution. Automatic parcellation, however, is extremely challenging due to high variation in the data, and the need for a large field of view at microscopic resolution. The performance of a recently proposed Convolutional Neural Network model that addresses this problem especially suffers from the naturally limited amount of expert annotations for training. To circumvent this limitation, we propose to pre-train neural networks on a self-supervised auxiliary task, predicting the 3D distance between two patches sampled from the same brain. Compared to a random initialization, fine-tuning from these networks results in significantly better segmentations. We show that the self-supervised model has implicitly learned to distinguish several cortical brain areas -- a strong indicator that the proposed auxiliary task is appropriate for cytoarchitectonic mapping.

##### Abstract (translated by Google)
人脑的Cytoarchitectonic parcellations作为多模式地图集框架中的解剖参考。它们基于对细胞体染色的组织切片进行分析并鉴定脑区之间的边界。事实上的标准涉及半自动，可重现的边界检测，但不能用微观分辨率的大量系列切片进行高通量成像。然而，由于数据的高度变化以及在微观分辨率下对大视野的需求，自动分段是非常具有挑战性的。最近提出的解决这个问题的卷积神经网络模型的性能尤其受到培训专家注释量的自然限制。为了规避这个限制，我们建议在自我监督的辅助任务上预训练神经网络，预测从同一个大脑采样的两个贴片之间的3D距离。与随机初始化相比，从这些网络进行微调可以得到明显更好的分段。我们表明，自我监督模型隐含地学会区分几个皮质脑区域 - 一个强有力的指标，提出的辅助任务适合于cytoarchitectonic映射。

##### URL
[http://arxiv.org/abs/1806.05104](http://arxiv.org/abs/1806.05104)

##### PDF
[http://arxiv.org/pdf/1806.05104](http://arxiv.org/pdf/1806.05104)

