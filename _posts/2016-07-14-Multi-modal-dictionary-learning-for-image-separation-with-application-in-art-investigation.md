---
layout: post
title: "Multi-modal dictionary learning for image separation with application in art investigation"
date: 2016-07-14 14:25:14
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Nikos Deligiannis, Joao F. C. Mota, Bruno Cornelis, Miguel R. D. Rodrigues, Ingrid Daubechies
mathjax: true
---

* content
{:toc}

##### Abstract
In support of art investigation, we propose a new source separation method that unmixes a single X-ray scan acquired from double-sided paintings. In this problem, the X-ray signals to be separated have similar morphological characteristics, which brings previous source separation methods to their limits. Our solution is to use photographs taken from the front and back-side of the panel to drive the separation process. The crux of our approach relies on the coupling of the two imaging modalities (photographs and X-rays) using a novel coupled dictionary learning framework able to capture both common and disparate features across the modalities using parsimonious representations; the common component models features shared by the multi-modal images, whereas the innovation component captures modality-specific information. As such, our model enables the formulation of appropriately regularized convex optimization procedures that lead to the accurate separation of the X-rays. Our dictionary learning framework can be tailored both to a single- and a multi-scale framework, with the latter leading to a significant performance improvement. Moreover, to improve further on the visual quality of the separated images, we propose to train coupled dictionaries that ignore certain parts of the painting corresponding to craquelure. Experimentation on synthetic and real data - taken from digital acquisition of the Ghent Altarpiece (1432) - confirms the superiority of our method against the state-of-the-art morphological component analysis technique that uses either fixed or trained dictionaries to perform image separation.

##### Abstract (translated by Google)
为了支持艺术调查，我们提出了一种新的源头分离方法，将从双面绘画获得的单个X射线扫描混合在一起。在这个问题中，要分离的X射线信号具有相似的形态特征，这使得之前的源分离方法达到了极限。我们的解决方案是使用从面板正面和背面拍摄的照片来驱动分离过程。我们的方法的关键依赖于两种成像模式（照片和X射线）的耦合使用一种新型的耦合词典学习框架，能够捕捉模式中的常见和不同的特征，使用简洁的表示;共同的组件模型特征由多模式图像共享，而创新组件捕获特定于模态的信息。因此，我们的模型能够制定适当的正则化凸优化程序，从而导致X射线的准确分离。我们的字典学习框架可以针对单一和多尺度的框架进行量身定制，后者可以显着提高性能。此外，为了进一步提高分离图像的视觉质量，我们建议训练混合字典，忽略绘画的某些部分相应的craquelure。对合成和真实数据的实验 - 从根特祭坛（1432）的数字采集中获得 - 证实了我们的方法与先进的形态成分分析技术相比的优越性，该技术使用固定或训练字典来执行图像分离。

##### URL
[https://arxiv.org/abs/1607.04147](https://arxiv.org/abs/1607.04147)

##### PDF
[https://arxiv.org/pdf/1607.04147](https://arxiv.org/pdf/1607.04147)

