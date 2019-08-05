---
layout: post
title: "Learning Lightweight Lane Detection CNNs by Self Attention Distillation"
date: 2019-08-02 12:13:34
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge Attention CNN Represenation_Learning Inference Detection
author: Yuenan Hou, Zheng Ma, Chunxiao Liu, Chen Change Loy
mathjax: true
---

* content
{:toc}

##### Abstract
Training deep models for lane detection is challenging due to the very subtle and sparse supervisory signals inherent in lane annotations. Without learning from much richer context, these models often fail in challenging scenarios, e.g., severe occlusion, ambiguous lanes, and poor lighting conditions. In this paper, we present a novel knowledge distillation approach, i.e., Self Attention Distillation (SAD), which allows a model to learn from itself and gains substantial improvement without any additional supervision or labels. Specifically, we observe that attention maps extracted from a model trained to a reasonable level would encode rich contextual information. The valuable contextual information can be used as a form of 'free' supervision for further representation learning through performing topdown and layer-wise attention distillation within the network itself. SAD can be easily incorporated in any feedforward convolutional neural networks (CNN) and does not increase the inference time. We validate SAD on three popular lane detection benchmarks (TuSimple, CULane and BDD100K) using lightweight models such as ENet, ResNet-18 and ResNet-34. The lightest model, ENet-SAD, performs comparatively or even surpasses existing algorithms. Notably, ENet-SAD has 20 x fewer parameters and runs 10 x faster compared to the state-of-the-art SCNN, while still achieving compelling performance in all benchmarks. Our code is available at https://github.com/cardwing/Codes-for-Lane-Detection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00821](http://arxiv.org/abs/1908.00821)

##### PDF
[http://arxiv.org/pdf/1908.00821](http://arxiv.org/pdf/1908.00821)

