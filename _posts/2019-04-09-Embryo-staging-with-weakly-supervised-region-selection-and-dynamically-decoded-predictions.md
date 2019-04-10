---
layout: post
title: "Embryo staging with weakly-supervised region selection and dynamically-decoded predictions"
date: 2019-04-09 02:03:08
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning Prediction
author: Tingfung Lau, Nathan Ng, Julian Gingold, Nina Desai, Julian McAuley, Zachary C. Lipton
mathjax: true
---

* content
{:toc}

##### Abstract
To optimize clinical outcomes, fertility clinics must strategically select which embryos to transfer. Common selection heuristics are formulas expressed in terms of the durations required to reach various developmental milestones, quantities historically annotated manually by experienced embryologists based on time-lapse EmbryoScope videos. We propose a new method for automatic embryo staging that exploits several sources of structure in this time-lapse data. First, noting that in each image the embryo occupies a small subregion, we jointly train a region proposal network with the downstream classifier to isolate the embryo. Notably, because we lack ground-truth bounding boxes, our we weakly supervise the region proposal network optimizing its parameters via reinforcement learning to improve the downstream classifier's loss. Moreover, noting that embryos reaching the blastocyst stage progress monotonically through earlier stages, we develop a dynamic-programming-based decoder that post-processes our predictions to select the most likely monotonic sequence of developmental stages. Our methods outperform vanilla residual networks and rival the best numbers in contemporary papers, as measured by both per-frame accuracy and transition prediction error, despite operating on smaller data than many.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04419](http://arxiv.org/abs/1904.04419)

##### PDF
[http://arxiv.org/pdf/1904.04419](http://arxiv.org/pdf/1904.04419)

