---
layout: post
title: "DeNet: Scalable Real-time Object Detection with Directed Sparse Sampling"
date: 2017-07-21 02:46:05
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Lachlan Tychsen-Smith, Lars Petersson
mathjax: true
---

* content
{:toc}

##### Abstract
We define the object detection from imagery problem as estimating a very large but extremely sparse bounding box dependent probability distribution. Subsequently we identify a sparse distribution estimation scheme, Directed Sparse Sampling, and employ it in a single end-to-end CNN based detection model. This methodology extends and formalizes previous state-of-the-art detection models with an additional emphasis on high evaluation rates and reduced manual engineering. We introduce two novelties, a corner based region-of-interest estimator and a deconvolution based CNN model. The resulting model is scene adaptive, does not require manually defined reference bounding boxes and produces highly competitive results on MSCOCO, Pascal VOC 2007 and Pascal VOC 2012 with real-time evaluation rates. Further analysis suggests our model performs particularly well when finegrained object localization is desirable. We argue that this advantage stems from the significantly larger set of available regions-of-interest relative to other methods. Source-code is available from: this https URL

##### Abstract (translated by Google)
我们将图像问题中的目标检测定义为估计非常大但非常稀疏的边界框依赖概率分布。随后，我们确定一个稀疏分布估计方案，定向稀疏采样，并将其用于单端到端的基于CNN的检测模型。这种方法扩展和形式化先前的最先进的检测模型，另外强调高评估率和减少手工工程。我们引入两个新颖的东西，一个基于角落的兴趣区域估计器和一个基于反卷积的CNN模型。由此产生的模型是场景适应性的，不需要手动定义的参考边界框，并在具有实时评估速率的MSCOCO，Pascal VOC 2007和Pascal VOC 2012上产生高度竞争的结果。进一步的分析表明，我们的模型表现特别好，当精细的对象本地化是可取的。我们认为，这种优势来源于相对于其他方法而言更大的可用兴趣区域集合。源代码可以从这个https URL获得

##### URL
[https://arxiv.org/abs/1703.10295](https://arxiv.org/abs/1703.10295)

##### PDF
[https://arxiv.org/pdf/1703.10295](https://arxiv.org/pdf/1703.10295)

