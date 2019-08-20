---
layout: post
title: "Feature Transfer Learning for Deep Face Recognition with Under-Represented Data"
date: 2019-08-19 05:52:42
categories: arXiv_CV
tags: arXiv_CV Face Transfer_Learning Recognition Face_Recognition
author: Xi Yin, Xiang Yu, Kihyuk Sohn, Xiaoming Liu, Manmohan Chandraker
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the large volume of face recognition datasets, there is a significant portion of subjects, of which the samples are insufficient and thus under-represented. Ignoring such significant portion results in insufficient training data. Training with under-represented data leads to biased classifiers in conventionally-trained deep networks. In this paper, we propose a center-based feature transfer framework to augment the feature space of under-represented subjects from the regular subjects that have sufficiently diverse samples. A Gaussian prior of the variance is assumed across all subjects and the variance from regular ones are transferred to the under-represented ones. This encourages the under-represented distribution to be closer to the regular distribution. Further, an alternating training regimen is proposed to simultaneously achieve less biased classifiers and a more discriminative feature representation. We conduct ablative study to mimic the under-represented datasets by varying the portion of under-represented classes on the MS-Celeb-1M dataset. Advantageous results on LFW, IJB-A and MS-Celeb-1M demonstrate the effectiveness of our feature transfer and training strategy, compared to both general baselines and state-of-the-art methods. Moreover, our feature transfer successfully presents smooth visual interpolation, which conducts disentanglement to preserve identity of a class while augmenting its feature space with non-identity variations such as pose and lighting.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.09014](http://arxiv.org/abs/1803.09014)

##### PDF
[http://arxiv.org/pdf/1803.09014](http://arxiv.org/pdf/1803.09014)

