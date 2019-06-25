---
layout: post
title: "Power-Grid Controller Anomaly Detection with Enhanced Temporal Deep Learning"
date: 2019-06-23 00:23:12
categories: arXiv_AI
tags: arXiv_AI Face Deep_Learning Detection
author: Zecheng He, Aswin Raghavan, Guangyuan Hu, Sek Chai, Ruby Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Controllers of security-critical cyber-physical systems, like the power grid, are a very important class of computer systems. Attacks against the control code of a power-grid system, especially zero-day attacks, can be catastrophic. Earlier detection of the anomalies can prevent further damage. However, detecting zero-day attacks is extremely challenging because they have no known code and have unknown behavior. Furthermore, if data collected from the controller is transferred to a server through networks for analysis and detection of anomalous behavior, this creates a very large attack surface and also delays detection. 
 In order to address this problem, we propose Reconstruction Error Distribution (RED) of Hardware Performance Counters (HPCs), and a data-driven defense system based on it. Specifically, we first train a temporal deep learning model, using only normal HPC readings from legitimate processes that run daily in these power-grid systems, to model the normal behavior of the power-grid controller. Then, we run this model using real-time data from commonly available HPCs. We use the proposed RED to enhance the temporal deep learning detection of anomalous behavior, by estimating distribution deviations from the normal behavior with an effective statistical test. Experimental results on a real power-grid controller show that we can detect anomalous behavior with high accuracy (&gt;99.9%), nearly zero false positives and short (&lt;360ms) latency.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.06496](http://arxiv.org/abs/1806.06496)

##### PDF
[http://arxiv.org/pdf/1806.06496](http://arxiv.org/pdf/1806.06496)

