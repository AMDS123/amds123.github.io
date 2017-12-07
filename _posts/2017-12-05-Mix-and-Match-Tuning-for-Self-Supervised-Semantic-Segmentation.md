---
layout: post
title: "Mix-and-Match Tuning for Self-Supervised Semantic Segmentation"
date: 2017-12-05 06:53:27
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation
author: Xiaohang Zhan, Ziwei Liu, Ping Luo, Xiaoou Tang, Chen Change Loy
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional networks for semantic image segmentation typically require large-scale labeled data, e.g. ImageNet and MS COCO, for network pre-training. To reduce annotation efforts, self-supervised semantic segmentation is recently proposed to pre-train a network without any human-provided labels. The key of this new form of learning is to design a proxy task (e.g. image colorization), from which a discriminative loss can be formulated on unlabeled data. Many proxy tasks, however, lack the critical supervision signals that could induce discriminative representation for the target image segmentation task. Thus self-supervision's performance is still far from that of supervised pre-training. In this study, we overcome this limitation by incorporating a "mix-and-match" (M&amp;M) tuning stage in the self-supervision pipeline. The proposed approach is readily pluggable to many self-supervision methods and does not use more annotated samples than the original process. Yet, it is capable of boosting the performance of target image segmentation task to surpass fully-supervised pre-trained counterpart. The improvement is made possible by better harnessing the limited pixel-wise annotations in the target dataset. Specifically, we first introduce the "mix" stage, which sparsely samples and mixes patches from the target set to reflect rich and diverse local patch statistics of target images. A "match" stage then forms a class-wise connected graph, which can be used to derive a strong triplet-based discriminative loss for fine-tuning the network. Our paradigm follows the standard practice in existing self-supervised studies and no extra data or label is required. With the proposed M&amp;M approach, for the first time, a self-supervision method can achieve comparable or even better performance compared to its ImageNet pre-trained counterpart on both PASCAL VOC2012 dataset and CityScapes dataset.

##### Abstract (translated by Google)
用于语义图像分割的深度卷积网络通常需要大规模标记的数据，例如， ImageNet和MS COCO进行网络预培训。为了减少注释的努力，最近提出了自我监督的语义分割，以预先训练没有任何人类提供的标签的网络。这种新的学习形式的关键是设计一个代理任务（如图像着色），由此可以在未标记的数据上制定一个区分性的损失。然而，许多代理任务缺乏可能导致目标图像分割任务的区分表示的关键监督信号。因此，自我监督的表现还远远没有受到监督的预训练。在这项研究中，我们通过在自我监督管道中加入“混合搭配”（M＆amp; M）调谐阶段来克服这个限制。所提出的方法很容易被插入到许多自我监督方法中，并且不使用比原始过程更多的注释样本。但是，它能够提高目标图像分割任务的性能，超过完全监督的预训练对象。通过更好地利用目标数据集中的有限像素方式的注释，使得改进成为可能。具体来说，我们首先介绍了“混合”阶段，它从目标集合中稀疏地采样和混合补丁，以反映目标图像的丰富多样的局部补丁统计。一个“匹配”阶段然后形成一个分类连通图，可以用来导出一个强大的基于三重的判别式损失微调网络。我们的范例遵循现有的自我监督研究的标准做法，不需要额外的数据或标签。与其在PASCAL VOC2012数据集和CityScapes数据集上的ImageNet预先训练的对应物相比，通过所提议的M＆amp; M方法，第一次，自监督方法可以实现相当的甚至更好的性能。

##### URL
[http://arxiv.org/abs/1712.00661](http://arxiv.org/abs/1712.00661)

##### PDF
[http://arxiv.org/pdf/1712.00661](http://arxiv.org/pdf/1712.00661)

