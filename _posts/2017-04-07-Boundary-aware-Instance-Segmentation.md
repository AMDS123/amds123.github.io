---
layout: post
title: "Boundary-aware Instance Segmentation"
date: 2017-04-07 01:43:57
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Zeeshan Hayder, Xuming He, Mathieu Salzmann
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of instance-level semantic segmentation, which aims at jointly detecting, segmenting and classifying every individual object in an image. In this context, existing methods typically propose candidate objects, usually as bounding boxes, and directly predict a binary mask within each such proposal. As a consequence, they cannot recover from errors in the object candidate generation process, such as too small or shifted boxes. In this paper, we introduce a novel object segment representation based on the distance transform of the object masks. We then design an object mask network (OMN) with a new residual-deconvolution architecture that infers such a representation and decodes it into the final binary object mask. This allows us to predict masks that go beyond the scope of the bounding boxes and are thus robust to inaccurate object candidates. We integrate our OMN into a Multitask Network Cascade framework, and learn the resulting boundary-aware instance segmentation (BAIS) network in an end-to-end manner. Our experiments on the PASCAL VOC 2012 and the Cityscapes datasets demonstrate the benefits of our approach, which outperforms the state-of-the-art in both object proposal generation and instance segmentation.

##### Abstract (translated by Google)
我们解决实例级语义分割问题，目的在于共同检测，分割和分类图像中的每个单独的对象。在这种情况下，现有方法通常提出候选对象，通常作为边界框，并直接预测每个这样的提议内的二进制掩码。因此，它们不能从对象候选生成过程中的错误中恢复，例如太小或移位的框。在本文中，我们基于对象掩码的距离变换引入了一种新的对象段表示。然后，我们用一个新的残差去卷积体系结构设计一个对象掩模网络（OMN），推断这种表示并将其解码为最终的二进制对象掩码。这使我们能够预测超出边界框范围的掩模，从而对不准确的候选对象有效。我们将我们的OMN集成到多任务网络级联框架中，并以端到端的方式学习由此产生的边界感知实例分段（BAIS）网络。我们在PASCAL VOC 2012和Cityscapes数据集上进行的实验证明了我们方法的优势，该方法在对象建议生成和实例细分方面均优于最新技术。

##### URL
[https://arxiv.org/abs/1612.03129](https://arxiv.org/abs/1612.03129)

##### PDF
[https://arxiv.org/pdf/1612.03129](https://arxiv.org/pdf/1612.03129)

