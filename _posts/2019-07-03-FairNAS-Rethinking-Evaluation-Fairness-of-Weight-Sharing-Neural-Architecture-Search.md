---
layout: post
title: "FairNAS: Rethinking Evaluation Fairness of Weight Sharing Neural Architecture Search"
date: 2019-07-03 10:50:38
categories: arXiv_AI
tags: arXiv_AI
author: Xiangxiang Chu, Bo Zhang, Ruijun Xu, Jixiang Li
mathjax: true
---

* content
{:toc}

##### Abstract
The ability to rank models by its real strength is the key to Neural Architecture Search. Traditional approaches adopt an incomplete training for such purpose which is still very costly. One-shot methods are thus devised to cut the expense by reusing the same set of weights. However, it is uncertain whether shared weights are truly effective. It is also unclear if a picked model is better because of its vigorous representational power or simply because it is overtrained. In order to remove the suspicion, we propose a novel idea called Fair Neural Architecture Search (FairNAS), in which a strict fairness constraint is enforced for fair inheritance and training. In this way, our supernet exhibits nice convergence and very high training accuracy. The performance of any sampled model loaded with shared weights from the supernet strongly correlates with that of stand-alone counterpart when trained fully. This result dramatically improves the searching efficiency, with a multi-objective reinforced evolutionary search backend, our pipeline generated a new set of state-of-the-art architectures on ImageNet: FairNAS-A attains 75.34% top-1 validation accuracy on ImageNet, FairNAS-B 75.10%, FairNAS-C 74.69%, even with lower multi-adds and/or fewer number of parameters compared with others. The models and their evaluation code are made publicly available online <a href="http://github.com/fairnas/FairNAS.">this http URL</a>

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01845](http://arxiv.org/abs/1907.01845)

##### PDF
[http://arxiv.org/pdf/1907.01845](http://arxiv.org/pdf/1907.01845)

