---
layout: post
title: "Towards Instance-level Image-to-Image Translation"
date: 2019-05-05 20:16:41
categories: arXiv_AI
tags: arXiv_AI Object_Detection Detection
author: Zhiqiang Shen, Mingyang Huang, Jianping Shi, Xiangyang Xue, Thomas Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Unpaired Image-to-image Translation is a new rising and challenging vision problem that aims to learn a mapping between unaligned image pairs in diverse domains. Recent advances in this field like MUNIT and DRIT mainly focus on disentangling content and style/attribute from a given image first, then directly adopting the global style to guide the model to synthesize new domain images. However, this kind of approaches severely incurs contradiction if the target domain images are content-rich with multiple discrepant objects. In this paper, we present a simple yet effective instance-aware image-to-image translation approach (INIT), which employs the fine-grained local (instance) and global styles to the target image spatially. The proposed INIT exhibits three import advantages: (1) the instance-level objective loss can help learn a more accurate reconstruction and incorporate diverse attributes of objects; (2) the styles used for target domain of local/global areas are from corresponding spatial regions in source domain, which intuitively is a more reasonable mapping; (3) the joint training process can benefit both fine and coarse granularity and incorporates instance information to improve the quality of global translation. We also collect a large-scale benchmark for the new instance-level translation task. We observe that our synthetic images can even benefit real-world vision tasks like generic object detection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.01744](http://arxiv.org/abs/1905.01744)

##### PDF
[http://arxiv.org/pdf/1905.01744](http://arxiv.org/pdf/1905.01744)

