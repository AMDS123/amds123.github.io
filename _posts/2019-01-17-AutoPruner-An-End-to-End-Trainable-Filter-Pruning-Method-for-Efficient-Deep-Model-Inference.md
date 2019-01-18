---
layout: post
title: "AutoPruner: An End-to-End Trainable Filter Pruning Method for Efficient Deep Model Inference"
date: 2019-01-17 06:11:48
categories: arXiv_CV
tags: arXiv_CV Inference
author: Jian-Hao Luo, Jianxin Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Channel pruning is an important family of methods to speed up deep model's inference. Previous filter pruning algorithms regard channel pruning and model fine-tuning as two independent steps. This paper argues that combining them into a single end-to-end trainable system will lead to better results. We propose an efficient channel selection layer, namely AutoPruner, to find less important filters automatically in a joint training manner. Our AutoPruner takes previous activation responses as an input and generates a true binary index code for pruning. Hence, all the filters corresponding to zero index values can be removed safely after training. We empirically demonstrate that the gradient information of this channel selection layer is also helpful for the whole model training. By gradually erasing several weak filters, we can prevent an excessive drop in model accuracy. Compared with previous state-of-the-art pruning algorithms (including training from scratch), AutoPruner achieves significantly better performance. Furthermore, ablation experiments show that the proposed novel mini-batch pooling and binarization operations are vital for the success of filter pruning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.08941](http://arxiv.org/abs/1805.08941)

##### PDF
[http://arxiv.org/pdf/1805.08941](http://arxiv.org/pdf/1805.08941)

