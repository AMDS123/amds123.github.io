---
layout: post
title: "DRD-Net: Detail-recovery Image Deraining via Context Aggregation Networks"
date: 2019-08-27 15:22:09
categories: arXiv_CV
tags: arXiv_CV Quantitative
author: Sen Deng, Mingqiang Wei, Jun Wang, Luming Liang, Haoran Xie, Meng Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Image deraining is a fundamental, yet not well-solved problem in computer vision and graphics. The traditional image deraining approaches commonly behave ineffectively in medium and heavy rain removal, while the learning-based ones lead to image degradations such as the loss of image details, halo artifacts and/or color distortion. Unlike existing image deraining approaches that lack the detail-recovery mechanism, we propose an end-to-end detail-recovery image deraining network (termed a DRD-Net) for single images. We for the first time introduce two sub-networks with a comprehensive loss function which synergize to derain and recover the lost details caused by deraining. We have three key contributions. First, we present a rain residual network to remove rain streaks from the rainy images, which combines the squeeze-and-excitation (SE) operation with residual blocks to make full advantage of spatial contextual information. Second, we design a new connection style block, named structure detail context aggregation block (SDCAB), which aggregates context feature information and has a large reception field. Third, benefiting from the SDCAB, we construct a detail repair network to encourage the lost details to return for eliminating image degradations. We have validated our approach on four recognized datasets (three synthetic and one real-world). Both quantitative and qualitative comparisons show that our approach outperforms the state-of-the-art deraining methods in terms of the deraining robustness and detail accuracy. The source code has been available for public evaluation and use on GitHub.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.10267](http://arxiv.org/abs/1908.10267)

##### PDF
[http://arxiv.org/pdf/1908.10267](http://arxiv.org/pdf/1908.10267)

