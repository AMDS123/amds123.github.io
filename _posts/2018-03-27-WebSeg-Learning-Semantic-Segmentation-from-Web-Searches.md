---
layout: post
title: "WebSeg: Learning Semantic Segmentation from Web Searches"
date: 2018-03-27 02:59:13
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation Weakly_Supervised Semantic_Segmentation
author: Qibin Hou, Ming-Ming Cheng, Jiangjiang Liu, Philip H.S. Torr
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we improve semantic segmentation by automatically learning from Flickr images associated with a particular keyword, without relying on any explicit user annotations, thus substantially alleviating the dependence on accurate annotations when compared to previous weakly supervised methods. To solve such a challenging problem, we leverage several low-level cues (such as saliency, edges, etc.) to help generate a proxy ground truth. Due to the diversity of web-crawled images, we anticipate a large amount of 'label noise' in which other objects might be present. We design an online noise filtering scheme which is able to deal with this label noise, especially in cluttered images. We use this filtering strategy as an auxiliary module to help assist the segmentation network in learning cleaner proxy annotations. Extensive experiments on the popular PASCAL VOC 2012 semantic segmentation benchmark show surprising good results in both our WebSeg (mIoU = 57.0%) and weakly supervised (mIoU = 63.3%) settings.

##### Abstract (translated by Google)
在本文中，我们通过自动学习与特定关键字相关联的Flickr图像来改进语义分割，而不依赖于任何明确的用户注释，从而与先前的弱监督方法相比显着减轻了对准确注释的依赖。为了解决这样一个具有挑战性的问题，我们利用几个低级提示（如显着性，边缘等）来帮助生成代理基本事实。由于网络抓取图像的多样性，我们预计会出现大量其他对象可能存在的“标签噪声”。我们设计了一个在线噪声滤波方案，能够处理这种标签噪声，特别是在混乱的图像中。我们使用这种过滤策略作为辅助模块来帮助分割网络学习清洁代理注释。在广受欢迎的PASCAL VOC 2012语义分割基准测试中进行的大量实验显示，我们的WebSeg（mIoU = 57.0％）和弱监督（mIoU = 63.3％）设置都有惊人的好结果。

##### URL
[https://arxiv.org/abs/1803.09859](https://arxiv.org/abs/1803.09859)

##### PDF
[https://arxiv.org/pdf/1803.09859](https://arxiv.org/pdf/1803.09859)

