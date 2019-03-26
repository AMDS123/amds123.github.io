---
layout: post
title: "Depth Augmented Networks with Optimal Fine-tuning"
date: 2019-03-25 06:43:26
categories: arXiv_CV
tags: arXiv_CV CNN Transfer_Learning Classification
author: Tasfia Shermin, Manzur Murshed, Shyh Wei Teng, Guojun Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNN) have been shown to achieve state-of-the-art performance in a significant number of computer vision tasks. Although they require large labelled training datasets to learn the CNN models, they have striking attributes of transferring learned representations from large source sets to smaller target sets by normal fine-tuning approaches. Prior research has shown that these techniques boost the performance on smaller target sets. In this paper, we demonstrate that growing network depth capacity beyond classification layer along with careful normalization and scaling scheme boosts fine-tuning by creating harmony between the pre-trained and new layers to adjust more to the target task. This indicates pre-trained classification layer holds high-level (global) image information that can be propagated through the newly introduced layers in fine-tuning. We evaluate our depth augmented networks following our designed incremental fine-tuning scheme on several benchmark datatsets and show that they outperform contemporary transfer learning approaches. On average, for fine-grained datasets we achieve up to 6.7% (AlexNet), 5.4% (VGG16) and for coarse datasets 9.3% (AlexNet), 8.7% (VGG16) improvement than normal fine-tuning. In addition, our in-depth analysis manifests freezing highly generic layers encourage better learning of target tasks. Furthermore, we have found that the learning rate for newly introduced layers of depth augmented networks depend on target set and size of new layers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10150](http://arxiv.org/abs/1903.10150)

##### PDF
[http://arxiv.org/pdf/1903.10150](http://arxiv.org/pdf/1903.10150)

