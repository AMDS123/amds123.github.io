---
layout: post
title: "ShelfNet for Fast Semantic Segmentation"
date: 2019-09-04 03:59:15
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Inference
author: Juntang Zhuang, Junlin Yang, Lin Gu, Nicha Dvornek
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present ShelfNet, a novel architecture for accurate fast semantic segmentation. Different from the single encoder-decoder structure, ShelfNet has multiple encoder-decoder branch pairs with skip connections at each spatial level, which looks like a shelf with multiple columns. The shelf-shaped structure can be viewed as an ensemble of multiple deep and shallow paths, thus improving accuracy. We significantly reduce computation burden by reducing channel number, at the same time achieving high accuracy with this unique structure. In addition, we propose a shared-weight strategy in the residual block which reduces parameter number without sacrificing performance. Compared with popular non real-time methods such as PSPNet, our ShelfNet achieves 4$\times$ faster inference speed with similar accuracy on PASCAL VOC dataset. Compared with real-time segmentation models such as BiSeNet, our model achieves higher accuracy at comparable speed on the Cityscapes Dataset, enabling the application in speed-demanding tasks such as street-scene understanding for autonomous driving. Furthermore, our ShelfNet achieves 79.0\% mIoU on Cityscapes Dataset with ResNet34 backbone, outperforming PSPNet and BiSeNet with large backbones such as ResNet101. Through extensive experiments, we validated the superior performance of ShelfNet. We provide link to the implementation \url{https://github.com/juntang-zhuang/ShelfNet-lw-cityscapes}.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11254](http://arxiv.org/abs/1811.11254)

##### PDF
[http://arxiv.org/pdf/1811.11254](http://arxiv.org/pdf/1811.11254)

