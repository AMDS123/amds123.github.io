---
layout: post
title: "HWNet v2: An Efficient Word Image Representation for Handwritten Documents"
date: 2018-02-17 05:12:03
categories: arXiv_CV
tags: arXiv_CV Image_Caption CNN Classification
author: Praveen Krishnan, C.V. Jawahar
mathjax: true
---

* content
{:toc}

##### Abstract
We present a framework for learning efficient holistic representation for handwritten word images. The proposed method uses a deep convolutional neural network with traditional classification loss. The major strengths of our work lie in: (i) the efficient usage of synthetic data to pre-train a deep network, (ii) an adapted version of ResNet-34 architecture with region of interest pooling (referred as HWNet v2) which learns discriminative features with variable sized word images, and (iii) realistic augmentation of training data with multiple scales and elastic distortion which mimics the natural process of handwriting. We further investigate the process of fine-tuning at various layers to reduce the domain gap between synthetic and real domain and also analyze the in-variances learned at different layers using recent visualization techniques proposed in literature. 
 Our representation leads to state of the art word spotting performance on standard handwritten datasets and historical manuscripts in different languages with minimal representation size. On the challenging IAM dataset, our method is first to report an mAP above 0.90 for word spotting with a representation size of just 32 dimensions. Further more, we also present results on printed document datasets in English and Indic scripts which validates the generic nature of the proposed framework for learning word image representation.

##### Abstract (translated by Google)
我们提出了一个学习手写单词图像的高效整体表示的框架。所提出的方法使用具有传统分类损失的深度卷积神经网络。我们工作的主要优势在于：（1）高效使用合成数据预训练深度网络;（2）具有感兴趣区域的ResNet-34体系结构（简称HWNet v2）的改编版本，它学习（iii）具有多种尺度和弹性变形的训练数据的真实增强，这些模拟手写的自然过程。我们进一步研究了各个层次的微调过程，以减少合成领域和实际领域之间的领域差距，并使用文献中提出的最新可视化技术分析不同层面学到的差异。
 我们的表现形式能够在标准的手写数据集和历史手稿中以最小的表示尺寸在不同语言中识别性能。在具有挑战性的IAM数据集上，我们的方法首先报告0.90以上的单词识别的mAP，其表示尺寸仅为32维。此外，我们还在印刷文件数据集上以英文和印度文字呈现结果，验证拟议框架学习单词图像表示的一般性质。

##### URL
[http://arxiv.org/abs/1802.06194](http://arxiv.org/abs/1802.06194)

##### PDF
[http://arxiv.org/pdf/1802.06194](http://arxiv.org/pdf/1802.06194)

