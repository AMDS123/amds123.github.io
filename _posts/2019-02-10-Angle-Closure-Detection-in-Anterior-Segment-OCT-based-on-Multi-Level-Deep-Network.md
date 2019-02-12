---
layout: post
title: "Angle-Closure Detection in Anterior Segment OCT based on Multi-Level Deep Network"
date: 2019-02-10 12:28:52
categories: arXiv_CV
tags: arXiv_CV Object_Detection Deep_Learning Detection
author: Huazhu Fu, Yanwu Xu, Stephen Lin, Damon Wing Kee Wong, Mani Baskaran, Meenakshi Mahesh, Tin Aung, Jiang Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Irreversible visual impairment is often caused by primary angle-closure glaucoma, which could be detected via Anterior Segment Optical Coherence Tomography (AS-OCT). In this paper, an automated system based on deep learning is presented for angle-closure detection in AS-OCT images. Our system learns a discriminative representation from training data that captures subtle visual cues not modeled by handcrafted features. A Multi-Level Deep Network (MLDN) is proposed to formulate this learning, which utilizes three particular AS-OCT regions based on clinical priors: the global anterior segment structure, local iris region, and anterior chamber angle (ACA) patch. In our method, a sliding window based detector is designed to localize the ACA region, which addresses ACA detection as a regression task. Then, three parallel sub-networks are applied to extract AS-OCT representations for the global image and at clinically-relevant local regions. Finally, the extracted deep features of these sub-networks are concatenated into one fully connected layer to predict the angle-closure detection result. In the experiments, our system is shown to surpass previous detection methods and other deep learning systems on two clinical AS-OCT datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.03585](http://arxiv.org/abs/1902.03585)

##### PDF
[http://arxiv.org/pdf/1902.03585](http://arxiv.org/pdf/1902.03585)

