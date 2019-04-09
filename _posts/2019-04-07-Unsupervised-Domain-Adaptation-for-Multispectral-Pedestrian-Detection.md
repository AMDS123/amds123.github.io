---
layout: post
title: "Unsupervised Domain Adaptation for Multispectral Pedestrian Detection"
date: 2019-04-07 17:24:28
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Dayan Guan, Xing Luo, Yanpeng Cao, Jiangxin Yang, Yanlong Cao, George Vosselman, Michael Ying Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Multimodal information (e.g., visible and thermal) can generate robust pedestrian detections to facilitate around-the-clock computer vision applications, such as autonomous driving and video surveillance. However, it still remains a crucial challenge to train a reliable detector working well in different multispectral pedestrian datasets without manual annotations. In this paper, we propose a novel unsupervised domain adaptation framework for multispectral pedestrian detection, by iteratively generating pseudo annotations and updating the parameters of our designed multispectral pedestrian detector on target domain. Pseudo annotations are generated using the detector trained on source domain, and then updated by fixing the parameters of detector and minimizing the cross entropy loss without back-propagation. Training labels are generated using the pseudo annotations by considering the characteristics of similarity and complementarity between well-aligned visible and infrared image pairs. The parameters of detector are updated using the generated labels by minimizing our defined multi-detection loss function with back-propagation. The optimal parameters of detector can be obtained after iteratively updating the pseudo annotations and parameters. Experimental results show that our proposed unsupervised multimodal domain adaptation method achieves significantly higher detection performance than the approach without domain adaptation, and is competitive with the supervised multispectral pedestrian detectors.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03692](http://arxiv.org/abs/1904.03692)

##### PDF
[http://arxiv.org/pdf/1904.03692](http://arxiv.org/pdf/1904.03692)

