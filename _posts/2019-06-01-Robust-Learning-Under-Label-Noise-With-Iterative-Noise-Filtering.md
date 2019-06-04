---
layout: post
title: "Robust Learning Under Label Noise With Iterative Noise-Filtering"
date: 2019-06-01 12:34:41
categories: arXiv_CV
tags: arXiv_CV Classification
author: Duc Tam Nguyen, Thi-Phuong-Nhung Ngo, Zhongyu Lou, Michael Klar, Laura Beggel, Thomas Brox
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of training a model under the presence of label noise. Current approaches identify samples with potentially incorrect labels and reduce their influence on the learning process by either assigning lower weights to them or completely removing them from the training set. In the first case the model however still learns from noisy labels; in the latter approach, good training data can be lost. In this paper, we propose an iterative semi-supervised mechanism for robust learning which excludes noisy labels but is still able to learn from the corresponding samples. To this end, we add an unsupervised loss term that also serves as a regularizer against the remaining label noise. We evaluate our approach on common classification tasks with different noise ratios. Our robust models outperform the state-of-the-art methods by a large margin. Especially for very large noise ratios, we achieve up to 20 % absolute improvement compared to the previous best model.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00216](http://arxiv.org/abs/1906.00216)

##### PDF
[http://arxiv.org/pdf/1906.00216](http://arxiv.org/pdf/1906.00216)

