---
layout: post
title: "A Closed-form Solution to Universal Style Transfer"
date: 2019-06-03 09:48:14
categories: arXiv_CV
tags: arXiv_CV Style_Transfer Quantitative Relation
author: Ming Lu, Hao Zhao, Anbang Yao, Yurong Chen, Feng Xu, Li Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Universal style transfer tries to explicitly minimize the losses in feature space, thus it does not require training on any pre-defined styles. It usually uses different layers of VGG network as the encoders and trains several decoders to invert the features into images. Therefore, the effect of style transfer is achieved by feature transform. Although plenty of methods have been proposed, a theoretical analysis of feature transform is still missing. In this paper, we first propose a novel interpretation by treating it as the optimal transport problem. Then, we demonstrate the relations of our formulation with former works like Adaptive Instance Normalization (AdaIN) and Whitening and Coloring Transform (WCT). Finally, we derive a closed-form solution under our formulation by additionally considering the content loss of Gatys. Comparatively, our solution can preserve better structure and achieve visually pleasing results. It is simple yet effective and we demonstrate the advantages both quantitatively and qualitatively. Besides, we hope our theoretical analysis can inspire future works in neural style transfer.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00668](http://arxiv.org/abs/1906.00668)

##### PDF
[http://arxiv.org/pdf/1906.00668](http://arxiv.org/pdf/1906.00668)

