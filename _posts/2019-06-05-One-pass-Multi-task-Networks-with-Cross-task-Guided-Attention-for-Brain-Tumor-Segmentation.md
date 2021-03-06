---
layout: post
title: "One-pass Multi-task Networks with Cross-task Guided Attention for Brain Tumor Segmentation"
date: 2019-06-05 02:50:08
categories: arXiv_AI
tags: arXiv_AI Segmentation Attention Prediction Relation
author: Chenhong Zhou, Changxing Ding, Xinchao Wang, Zhentai Lu, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Class imbalance has been one of the major challenges for medical image segmentation. The model cascade (MC) strategy significantly alleviates class imbalance issue. In spite of its outstanding performance, this method leads to an undesired system complexity and meanwhile ignores the relevance among the models. To handle these flaws of MC, we propose in this paper a light-weight deep model, i.e., the One-pass Multi-task Network (OM-Net) to solve class imbalance better than MC and require only one-pass computation for brain tumor segmentation. First, OM-Net integrates the separate segmentation tasks into one deep model. Second, to optimize OM-Net more effectively, we take advantage of the correlation among tasks to design an online training data transfer strategy and a curriculum learning-based training strategy. Third, we further propose to share prediction results between tasks, which enables us to design a cross-task guided attention (CGA) module. With the guidance of prediction results provided by the previous task, CGA can adaptively recalibrate channel-wise feature responses based on the category-specific statistics. Finally, a simple yet effective post-processing method is introduced to refine the segmentation results of the proposed attention network. Extensive experiments are performed to justify the effectiveness of the proposed techniques. Most impressively, we achieve state-of-the-art performance on the BraTS 2015 and BraTS 2017 datasets. With the proposed approaches, we also won the joint third place in the BraTS 2018 challenge among 64 participating teams. We will make the code publicly available at https://github.com/chenhong-zhou/OM-Net.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01796](http://arxiv.org/abs/1906.01796)

##### PDF
[http://arxiv.org/pdf/1906.01796](http://arxiv.org/pdf/1906.01796)

