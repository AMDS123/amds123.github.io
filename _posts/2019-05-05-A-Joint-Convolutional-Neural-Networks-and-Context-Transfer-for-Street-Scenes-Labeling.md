---
layout: post
title: "A Joint Convolutional Neural Networks and Context Transfer for Street Scenes Labeling"
date: 2019-05-05 01:24:19
categories: arXiv_CV
tags: arXiv_CV Image_Caption CNN Inference
author: Qi Wang, Junyu Gao, Yuan Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
Street scene understanding is an essential task for autonomous driving. One important step towards this direction is scene labeling, which annotates each pixel in the images with a correct class label. Although many approaches have been developed, there are still some weak points. Firstly, many methods are based on the hand-crafted features whose image representation ability is limited. Secondly, they can not label foreground objects accurately due to the dataset bias. Thirdly, in the refinement stage, the traditional Markov Random Filed (MRF) inference is prone to over smoothness. For improving the above problems, this paper proposes a joint method of priori convolutional neural networks at superpixel level (called as ``priori s-CNNs'') and soft restricted context transfer. Our contributions are threefold: (1) A priori s-CNNs model that learns priori location information at superpixel level is proposed to describe various objects discriminatingly; (2) A hierarchical data augmentation method is presented to alleviate dataset bias in the priori s-CNNs training stage, which improves foreground objects labeling significantly; (3) A soft restricted MRF energy function is defined to improve the priori s-CNNs model's labeling performance and reduce the over smoothness at the same time. The proposed approach is verified on CamVid dataset (11 classes) and SIFT Flow Street dataset (16 classes) and achieves competitive performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.01574](http://arxiv.org/abs/1905.01574)

##### PDF
[http://arxiv.org/pdf/1905.01574](http://arxiv.org/pdf/1905.01574)

