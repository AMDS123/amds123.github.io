---
layout: post
title: "Progressive NAPSAC: sampling from gradually growing neighborhoods"
date: 2019-06-05 20:28:18
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Daniel Barath, Maksym Ivashechkin, Jiri Matas
mathjax: true
---

* content
{:toc}

##### Abstract
We propose Progressive NAPSAC, P-NAPSAC in short, which merges the advantages of local and global sampling by drawing samples from gradually growing neighborhoods. Exploiting the fact that nearby points are more likely to originate from the same geometric model, P-NAPSAC finds local structures earlier than global samplers. We show that the progressive spatial sampling in P-NAPSAC can be integrated with PROSAC sampling, which is applied to the first, location-defining, point. P-NAPSAC is embedded in USAC, a state-of-the-art robust estimation pipeline, which we further improve by implementing its local optimization as in Graph-Cut RANSAC. We call the resulting estimator USAC*. The method is tested on homography and fundamental matrix fitting on a total of 10,691 models from seven publicly available datasets. USAC* with P-NAPSAC outperforms reference methods in terms of speed on all problems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02295](http://arxiv.org/abs/1906.02295)

##### PDF
[http://arxiv.org/pdf/1906.02295](http://arxiv.org/pdf/1906.02295)

