---
layout: post
title: "OCNet: Object Context Network for Scene Parsing"
date: 2018-09-04 12:22:10
categories: arXiv_CV
tags: arXiv_CV Attention
author: Yuhui Yuan, Jingdong Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Context is essential for various computer vision tasks. The state-of-the-art scene parsing methods have exploited the effectiveness of the context defined over image-level. Such context carries the mixture of objects belonging to different categories. 
 According to that the label of each pixel $\mathit{P}$ is defined as the category of the object it belongs to, we propose the pixel-wise Object Context that consists of the objects belonging to the same category with pixel $\mathit{P}$. The representation of pixel $\mathit{P}$'s object context is the aggregation of all the features that belong to the pixels sharing the same category with $\mathit{P}$. Since the ground truth objects that the pixel $\mathit{P}$ belonging to is unavailable, we employ the self-attention method to approximate the objects by learning a pixel-wise similarity map. 
 We further propose the Pyramid Object Context and Atrous Spatial Pyramid Object Context to capture context of multiple scales. Based on the object context, we introduce the OCNet and show that OCNet achieves state-of-the-art performance on both Cityscapes benchmark and ADE20K benchmark. The code of OCNet will be made available at https://github.com/PkuRainBow/OCNet.

##### Abstract (translated by Google)
上下文对于各种计算机视觉任务至关重要最先进的场景解析方法利用了在图像级别定义的上下文的有效性。这种上下文携带属于不同类别的对象的混合。
 根据每个像素$ \ mathit {P} $的标签被定义为它所属的对象的类别，我们提出像素方式的对象上下文，它由属于同一类别的对象组成，带有像素$ \ mathit {P} $。像素$ \ mathit {P} $的对象上下文的表示是属于与$ \ mathit {P} $共享相同类别的像素的所有特征的聚合。由于属于的像素$ \ mathit {P} $的基础事实对象不可用，我们采用自我关注方法通过学习像素相似度图来近似对象。
 我们进一步提出金字塔对象上下文和Atrous空间金字塔对象上下文来捕获多个尺度的上下文。基于对象上下文，我们介绍了OCNet，并表明OCNet在Cityscapes基准测试和ADE20K基准测试中都达到了最先进的性能。 OCNet的代码将在https://github.com/PkuRainBow/OCNet上提供。

##### URL
[http://arxiv.org/abs/1809.00916](http://arxiv.org/abs/1809.00916)

##### PDF
[http://arxiv.org/pdf/1809.00916](http://arxiv.org/pdf/1809.00916)

