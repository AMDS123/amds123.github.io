---
layout: post
title: "Interpretable and Generalizable Deep Image Matching with Adaptive Convolutions"
date: 2019-04-23 17:03:13
categories: arXiv_CV
tags: arXiv_CV Re-identification Face Person_Re-identification Transfer_Learning Represenation_Learning Recognition Face_Recognition
author: Shengcai Liao, Ling Shao
mathjax: true
---

* content
{:toc}

##### Abstract
For image matching tasks, like face recognition and person re-identification, existing deep networks often focus on representation learning. However, without domain adaptation or transfer learning, the learned model is fixed as is, which is not adaptable to handle various unseen scenarios. In this paper, beyond representation learning, we consider how to formulate image matching directly in deep feature maps. We treat image matching as finding local correspondences in feature maps, and construct adaptive convolution kernels on the fly to achieve local matching. In this way, the matching process and result is interpretable, and this explicit matching is more generalizable than representation features to unseen scenarios, such as unknown misalignments, pose or viewpoint changes. To facilitate end-to-end training of such an image matching architecture, we further build a class memory module to cache feature maps of the most recent samples of each class, so as to compute image matching losses for metric learning. The proposed method is preliminarily validated on the person re-identification task. Through direct cross-dataset evaluation without further transfer learning, it achieves better results than many transfer learning methods. Besides, a model-free temporal cooccurrence based score weighting method is proposed, which improves the performance to a further extent, resulting in state-of-the-art results in cross-dataset evaluation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10424](http://arxiv.org/abs/1904.10424)

##### PDF
[http://arxiv.org/pdf/1904.10424](http://arxiv.org/pdf/1904.10424)

