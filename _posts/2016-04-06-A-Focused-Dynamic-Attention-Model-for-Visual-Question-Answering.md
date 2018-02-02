---
layout: post
title: "A Focused Dynamic Attention Model for Visual Question Answering"
date: 2016-04-06 05:16:10
categories: arXiv_CV
tags: arXiv_CV Object_Detection QA Attention RNN Detection VQA Recognition
author: Ilija Ilievski, Shuicheng Yan, Jiashi Feng
mathjax: true
---

* content
{:toc}

##### Abstract
Visual Question and Answering (VQA) problems are attracting increasing interest from multiple research disciplines. Solving VQA problems requires techniques from both computer vision for understanding the visual contents of a presented image or video, as well as the ones from natural language processing for understanding semantics of the question and generating the answers. Regarding visual content modeling, most of existing VQA methods adopt the strategy of extracting global features from the image or video, which inevitably fails in capturing fine-grained information such as spatial configuration of multiple objects. Extracting features from auto-generated regions -- as some region-based image recognition methods do -- cannot essentially address this problem and may introduce some overwhelming irrelevant features with the question. In this work, we propose a novel Focused Dynamic Attention (FDA) model to provide better aligned image content representation with proposed questions. Being aware of the key words in the question, FDA employs off-the-shelf object detector to identify important regions and fuse the information from the regions and global features via an LSTM unit. Such question-driven representations are then combined with question representation and fed into a reasoning unit for generating the answers. Extensive evaluation on a large-scale benchmark dataset, VQA, clearly demonstrate the superior performance of FDA over well-established baselines.

##### Abstract (translated by Google)
视觉问答（VQA）问题越来越引起越来越多的研究学科的兴趣。解决VQA问题需要计算机视觉技术来理解所呈现的图像或视频的视觉内容，以及来自自然语言处理的技术以理解问题的语义并生成答案。在视觉内容建模方面，现有的大多数VQA方法都采用从图像或视频中提取全局特征的策略，难以捕捉到多个对象的空间配置等细粒度信息。从自动生成的区域中提取特征 - 就像一些基于区域的图像识别方法一样 - 本质上不能解决这个问题，并且可能会引入一些压倒性的不相关的特征。在这项工作中，我们提出了一种新颖的聚焦动态注意（FDA）模型来提供更好的对齐图像内容表示与提出的问题。意识到问题中的关键词，FDA采用现成的物体检测器来识别重要区域，并通过LSTM单元融合来自区域和全局特征的信息。然后将这样的问题驱动的表示与问题表示相结合，并送入推理单元以产生答案。对大规模基准数据集VQA的广泛评估清楚地表明了FDA相对于完善的基线的卓越性能。

##### URL
[https://arxiv.org/abs/1604.01485](https://arxiv.org/abs/1604.01485)

##### PDF
[https://arxiv.org/pdf/1604.01485](https://arxiv.org/pdf/1604.01485)

