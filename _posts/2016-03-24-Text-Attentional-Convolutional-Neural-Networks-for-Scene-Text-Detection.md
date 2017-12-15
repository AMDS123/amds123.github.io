---
layout: post
title: "Text-Attentional Convolutional Neural Networks for Scene Text Detection"
date: 2016-03-24 23:25:52
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Text_Classification CNN Classification Deep_Learning Detection
author: Tong He, Weilin Huang, Yu Qiao, Jian Yao
mathjax: true
---

* content
{:toc}

##### Abstract
Recent deep learning models have demonstrated strong capabilities for classifying text and non-text components in natural images. They extract a high-level feature computed globally from a whole image component (patch), where the cluttered background information may dominate true text features in the deep representation. This leads to less discriminative power and poorer robustness. In this work, we present a new system for scene text detection by proposing a novel Text-Attentional Convolutional Neural Network (Text-CNN) that particularly focuses on extracting text-related regions and features from the image components. We develop a new learning mechanism to train the Text-CNN with multi-level and rich supervised information, including text region mask, character label, and binary text/nontext information. The rich supervision information enables the Text-CNN with a strong capability for discriminating ambiguous texts, and also increases its robustness against complicated background components. The training process is formulated as a multi-task learning problem, where low-level supervised information greatly facilitates main task of text/non-text classification. In addition, a powerful low-level detector called Contrast- Enhancement Maximally Stable Extremal Regions (CE-MSERs) is developed, which extends the widely-used MSERs by enhancing intensity contrast between text patterns and background. This allows it to detect highly challenging text patterns, resulting in a higher recall. Our approach achieved promising results on the ICDAR 2013 dataset, with a F-measure of 0.82, improving the state-of-the-art results substantially.

##### Abstract (translated by Google)
最近的深度学习模型已经证明了在自然图像中分类文本和非文本分量的强大能力。他们从整个图像组件（补丁）中提取全局计算的高级特征，其中杂乱的背景信息可以支配深度表示中的真实文本特征。这导致较小的辨别力和较差的鲁棒性。在这项工作中，我们提出了一个新的文本检测系统，提出了一种新的文本 - 注意卷积神经网络（Text-CNN），特别关注于从图像中提取文本相关的区域和特征。我们开发了一个新的学习机制来训练Text-CNN多层次，丰富的监督信息，包括文本区域掩码，字符标签和二进制文本/非文本信息。丰富的监督信息使得Text-CNN具有很强的识别歧义文本的能力，并且增强了对复杂背景成分的鲁棒性。将训练过程表述为多任务学习问题，低层次的监督信息极大地促进了文本/非文本分类的主要任务。此外，还开发了一种称为对比增强最大稳定极值区域（CE-MSER）的强大的低级别检测器，通过增强文本模式和背景之间的强度对比度来扩展广泛使用的MSER。这使得它可以检测到极具挑战性的文本模式，从而提高召回率。我们的方法在ICDAR 2013数据集上取得了令人满意的结果，F值为0.82，大大改善了最新的结果。

##### URL
[https://arxiv.org/abs/1510.03283](https://arxiv.org/abs/1510.03283)

##### PDF
[https://arxiv.org/pdf/1510.03283](https://arxiv.org/pdf/1510.03283)

