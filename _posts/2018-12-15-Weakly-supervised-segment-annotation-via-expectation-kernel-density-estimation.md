---
layout: post
title: "Weakly supervised segment annotation via expectation kernel density estimation"
date: 2018-12-15 03:31:32
categories: arXiv_CV
tags: arXiv_CV Weakly_Supervised
author: Liantao Wang, Qingwu Li, Jianfeng Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Since the labelling for the positive images/videos is ambiguous in weakly supervised segment annotation, negative mining based methods that only use the intra-class information emerge. In these methods, negative instances are utilized to penalize unknown instances to rank their likelihood of being an object, which can be considered as a voting in terms of similarity. However, these methods 1) ignore the information contained in positive bags, 2) only rank the likelihood but cannot generate an explicit decision function. In this paper, we propose a voting scheme involving not only the definite negative instances but also the ambiguous positive instances to make use of the extra useful information in the weakly labelled positive bags. In the scheme, each instance votes for its label with a magnitude arising from the similarity, and the ambiguous positive instances are assigned soft labels that are iteratively updated during the voting. It overcomes the limitations of voting using only the negative bags. We also propose an expectation kernel density estimation (eKDE) algorithm to gain further insight into the voting mechanism. Experimental results demonstrate the superiority of our scheme beyond the baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.06228](http://arxiv.org/abs/1812.06228)

##### PDF
[http://arxiv.org/pdf/1812.06228](http://arxiv.org/pdf/1812.06228)

