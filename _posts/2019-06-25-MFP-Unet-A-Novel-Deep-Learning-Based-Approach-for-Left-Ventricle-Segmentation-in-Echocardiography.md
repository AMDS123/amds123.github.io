---
layout: post
title: "MFP-Unet: A Novel Deep Learning Based Approach for Left Ventricle Segmentation in Echocardiography"
date: 2019-06-25 12:56:27
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Deep_Learning Quantitative Relation
author: Shakiba Moradi, Azin Alizadehasl, Jan Dhooge, Isaac Shiri, Niki Oveisi, Mehrdad Oveisi, Majid Maleki, Mostafa Ghelich-Oghli
mathjax: true
---

* content
{:toc}

##### Abstract
Segmentation of the Left ventricle (LV) is a crucial step for quantitative measurements such as area, volume, and ejection fraction. However, the automatic LV segmentation in 2D echocardiographic images is a challenging task due to ill-defined borders, and operator dependence issues (insufficient reproducibility). U-net, which is a well-known architecture in medical image segmentation, addressed this problem through an encoder-decoder path. Despite outstanding overall performance, U-net ignores the contribution of all semantic strengths in the segmentation procedure. In the present study, we have proposed a novel architecture to tackle this drawback. Feature maps in all levels of the decoder path of U-net are concatenated, their depths are equalized, and up-sampled to a fixed dimension. This stack of feature maps would be the input of the semantic segmentation layer. The proposed network yielded state-of-the-art results when comparing with results from U-net, dilated U-net, and deeplabv3, using the same dataset. An average Dice Metric (DM) of 0.945, Hausdorff Distance (HD) of 1.62, Jaccard Coefficient (JC) of 0.97, and Mean Absolute Distance (MAD) of 1.32 are achieved. The correlation graph, bland-altman analysis, and box plot showed a great agreement between automatic and manually calculated volume, area, and length.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.10486](http://arxiv.org/abs/1906.10486)

##### PDF
[http://arxiv.org/pdf/1906.10486](http://arxiv.org/pdf/1906.10486)

