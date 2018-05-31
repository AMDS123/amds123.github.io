---
layout: post
title: "Superpixel-enhanced Pairwise Conditional Random Field for Semantic Segmentation"
date: 2018-05-29 22:59:32
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Inference RNN
author: Li Sulimowicz, Ishfaq Ahmad, Alexander Aved
mathjax: true
---

* content
{:toc}

##### Abstract
Superpixel-based Higher-order Conditional Random Fields (CRFs) are effective in enforcing long-range consistency in pixel-wise labeling problems, such as semantic segmentation. However, their major short coming is considerably longer time to learn higher-order potentials and extra hyperparameters and/or weights compared with pairwise models. This paper proposes a superpixel-enhanced pairwise CRF framework that consists of the conventional pairwise as well as our proposed superpixel-enhanced pairwise (SP-Pairwise) potentials. SP-Pairwise potentials incorporate the superpixel-based higher-order cues by conditioning on a segment filtered image and share the same set of parameters as the conventional pairwise potentials. Therefore, the proposed superpixel-enhanced pairwise CRF has a lower time complexity in parameter learning and at the same time it outperforms higher-order CRF in terms of inference accuracy. Moreover, the new scheme takes advantage of the pre-trained pairwise models by reusing their parameters and/or weights, which provides a significant accuracy boost on the basis of CRF-RNN even without training. Experiments on MSRC-21 and PASCAL VOC 2012 dataset confirm the effectiveness of our method.

##### Abstract (translated by Google)
基于超像素的高阶条件随机场（CRF）在像素方式标记问题（例如语义分割）中实施长距离一致性是有效的。然而，与成对模型相比，他们的主要缺点是要学习更高阶潜能和额外超参数和/或权重的时间要长得多。本文提出了一种超像素增强的成对CRF框架，其由常规成对以及我们提出的超像素增强成对（SP-成对）电势组成。 SP-成对电位通过调节分段滤波图像并与基于超像素的高阶提示相结合，并与传统成对电位共享相同的一组参数。因此，所提出的超像素增强型成对CRF在参数学习中具有较低的时间复杂度，并且同时在推理精度方面优于高阶CRF。此外，新方案通过重用其参数和/或权重来利用预先训练的成对模型，这在CRF-RNN的基础上甚至在没有训练的情况下提供显着的准确度提升。 MSRC-21和PASCAL VOC 2012数据集上的实验证实了我们方法的有效性。

##### URL
[https://arxiv.org/abs/1805.11737](https://arxiv.org/abs/1805.11737)

##### PDF
[https://arxiv.org/pdf/1805.11737](https://arxiv.org/pdf/1805.11737)

