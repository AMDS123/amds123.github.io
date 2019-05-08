---
layout: post
title: "Learning Unsupervised Multi-View Stereopsis via Robust Photometric Consistency"
date: 2019-05-07 17:45:22
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Tejas Khot, Shubham Agrawal, Shubham Tulsiani, Christoph Mertz, Simon Lucey, Martial Hebert
mathjax: true
---

* content
{:toc}

##### Abstract
We present a learning based approach for multi-view stereopsis (MVS). While current deep MVS methods achieve impressive results, they crucially rely on ground-truth 3D training data, and acquisition of such precise 3D geometry for supervision is a major hurdle. Our framework instead leverages photometric consistency between multiple views as supervisory signal for learning depth prediction in a wide baseline MVS setup. However, naively applying photo consistency constraints is undesirable due to occlusion and lighting changes across views. To overcome this, we propose a robust loss formulation that: a) enforces first order consistency and b) for each point, selectively enforces consistency with some views, thus implicitly handling occlusions. We demonstrate our ability to learn MVS without 3D supervision using a real dataset, and show that each component of our proposed robust loss results in a significant improvement. We qualitatively observe that our reconstructions are often more complete than the acquired ground truth, further showing the merits of this approach. Lastly, our learned model generalizes to novel settings, and our approach allows adaptation of existing CNNs to datasets without ground-truth 3D by unsupervised finetuning. Project webpage: this https URL

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.02706](https://arxiv.org/abs/1905.02706)

##### PDF
[https://arxiv.org/pdf/1905.02706](https://arxiv.org/pdf/1905.02706)

