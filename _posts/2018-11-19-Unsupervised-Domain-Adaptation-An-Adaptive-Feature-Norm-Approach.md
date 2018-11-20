---
layout: post
title: "Unsupervised Domain Adaptation: An Adaptive Feature Norm Approach"
date: 2018-11-19 02:04:58
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge
author: Ruijia Xu, Guanbin Li, Jihan Yang, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised domain adaptation aims to mitigate the domain shift when transferring knowledge from a supervised source domain to an unsupervised target domain. Adversarial Feature Alignment has been successfully explored to minimize the domain discrepancy. However, existing methods are usually struggling to optimize mixed learning objectives and vulnerable to negative transfer when two domains do not share the identical label space. In this paper, we empirically reveal that the erratic discrimination of target domain mainly reflects in its much lower feature norm value with respect to that of the source domain. We present a non-parametric Adaptive Feature Norm AFN approach, which is independent of the association between label spaces of the two domains. We demonstrate that adapting feature norms of source and target domains to achieve equilibrium over a large range of values can result in significant domain transfer gains. Without bells and whistles but a few lines of code, our method largely lifts the discrimination of target domain (23.7\% from the Source Only in VisDA2017) and achieves the new state of the art under the vanilla setting. Furthermore, as our approach does not require to deliberately align the feature distributions, it is robust to negative transfer and can outperform the existing approaches under the partial setting by an extremely large margin (9.8\% on Office-Home and 14.1\% on VisDA2017). Code is available at https://github.com/jihanyang/AFN. We are responsible for the reproducibility of our method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07456](http://arxiv.org/abs/1811.07456)

##### PDF
[http://arxiv.org/pdf/1811.07456](http://arxiv.org/pdf/1811.07456)

