---
layout: post
title: "Language-Based Image Editing with Recurrent Attentive Models"
date: 2017-11-16 19:10:21
categories: arXiv_CV
tags: arXiv_CV Segmentation Inference
author: Jianbo Chen, Yelong Shen, Jianfeng Gao, Jingjing Liu, Xiaodong Liu
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate the problem of Language-Based Image Editing (LBIE) in this work. Given a source image and a natural language description, we want to generate a target image by editing the source im- age based on the description. We propose a generic modeling framework for two sub-tasks of LBIE: language-based image segmentation and image colorization. The framework uses recurrent attentive models to fuse image and language features. Instead of using a fixed step size, we introduce for each re- gion of the image a termination gate to dynamically determine in each inference step whether to continue extrapolating additional information from the textual description. The effectiveness of the framework has been validated on three datasets. First, we introduce a synthetic dataset, called CoSaL, to evaluate the end-to-end performance of our LBIE system. Second, we show that the framework leads to state-of-the- art performance on image segmentation on the ReferIt dataset. Third, we present the first language-based colorization result on the Oxford-102 Flowers dataset, laying the foundation for future research.

##### Abstract (translated by Google)
我们在这项工作中调查基于语言的图像编辑（LBIE）的问题。给定源图像和自然语言描述，我们希望通过基于描述编辑源图像来生成目标图像。我们提出了LBIE的两个子任务的通用建模框架：基于语言的图像分割和图像着色。该框架使用经常性的注意模型来融合图像和语言特征。我们不是使用固定步长，而是为图像的每个区域引入一个终止门，以便在每个推理步骤中动态确定是否继续从文本描述中外推附加信息。框架的有效性已经在三个数据集上得到验证。首先，我们引入一个称为CoSaL的综合数据集来评估LBIE系统的端到端性能。其次，我们展示了该框架在ReferIt数据集上的图像分割方面的最新性能。第三，我们在Oxford-102 Flowers数据集中提出了第一个基于语言的着色结果，为今后的研究奠定了基础。

##### URL
[https://arxiv.org/abs/1711.06288](https://arxiv.org/abs/1711.06288)

##### PDF
[https://arxiv.org/pdf/1711.06288](https://arxiv.org/pdf/1711.06288)

