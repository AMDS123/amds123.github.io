---
layout: post
title: "AutoPruner: An End-to-End Trainable Filter Pruning Method for Efficient Deep Model Inference"
date: 2018-05-23 03:05:48
categories: arXiv_CV
tags: arXiv_CV Inference
author: Jian-Hao Luo, Jianxin Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Channel pruning is an important family of methods to speedup deep model's inference. Previous filter pruning algorithms regard channel pruning and model fine-tuning as two independent steps. This paper argues that combining them in a single end-to-end trainable system will lead to better results. We propose an efficient channel selection layer, namely AutoPruner, to find less important filters automatically in a joint training manner. AutoPruner takes previous activation responses as input and generates a true binary index code for pruning. Hence, all the filters corresponding to zero index values can be removed safely after training. We empirically demonstrate that the gradient information of this channel selection layer is also helpful for the whole model training. Compared with previous state-of-the-art pruning algorithms, AutoPruner achieves significantly better performance. Furthermore, ablation experiments show that the proposed novel mini-batch pooling and binarization operations are vital for the success of filter pruning.

##### Abstract (translated by Google)
通道修剪是加速深度模型推断的重要方法。先前的滤波器修剪算法将信道修剪和模型微调视为两个独立的步骤。本文认为，将它们结合到一个单一的端到端可训练系统中将会带来更好的结果。我们提出了一个有效的频道选择层，即AutoPruner，以联合培训的方式自动找到不太重要的过滤器。 AutoPruner将先前的激活响应作为输入并生成用于修剪的真正的二进制索引代码。因此，所有与零指标值对应的滤波器可以在训练后安全移除。我们通过实证证明，该信道选择层的梯度信息对整个模型训练也有帮助。与以前最先进的修剪算法相比，AutoPruner实现了更好的性能。此外，消融实验表明，所提出的新型小批量池化和二元化操作对于过滤器修剪的成功至关重要。

##### URL
[http://arxiv.org/abs/1805.08941](http://arxiv.org/abs/1805.08941)

##### PDF
[http://arxiv.org/pdf/1805.08941](http://arxiv.org/pdf/1805.08941)

