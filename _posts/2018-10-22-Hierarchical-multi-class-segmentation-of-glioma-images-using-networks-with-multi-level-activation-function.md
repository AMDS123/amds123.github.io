---
layout: post
title: "Hierarchical multi-class segmentation of glioma images using networks with multi-level activation function"
date: 2018-10-22 18:22:34
categories: arXiv_CV
tags: arXiv_CV Segmentation Relation
author: Xiaobin Hu, Hongwei Li, Yu Zhao, Chao Dong, Marie Piraud
mathjax: true
---

* content
{:toc}

##### Abstract
For many segmentation tasks, especially for the biomedical image, the topological prior is vital information which is useful to exploit. The containment/nesting is a typical inter-class geometric relationship. In the MICCAI Brain tumor segmentation challenge, with its three hierarchically nested classes 'whole tumor', 'tumor core', 'active tumor', the nested classes relationship is introduced into the 3D-residual-Unet architecture. The network comprises a context aggregation pathway and a localization pathway, which encodes increasingly abstract representation of the input as going deeper into the network, and then recombines these representations with shallower features to precisely localize the interest domain via a localization path. The nested-class-prior is combined by proposing the multi-class activation function and its corresponding loss function. The model is trained on the training dataset of Brats2018, and 20% of the dataset is regarded as the validation dataset to determine parameters. When the parameters are fixed, we retrain the model on the whole training dataset. The performance achieved on the validation leaderboard is 86%, 77% and 72% Dice scores for the whole tumor, enhancing tumor and tumor core classes without relying on ensembles or complicated post-processing steps. Based on the same start-of-the-art network architecture, the accuracy of nested-class (enhancing tumor) is reasonably improved from 69% to 72% compared with the traditional Softmax-based method which blind to topological prior.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.09488](http://arxiv.org/abs/1810.09488)

##### PDF
[http://arxiv.org/pdf/1810.09488](http://arxiv.org/pdf/1810.09488)

