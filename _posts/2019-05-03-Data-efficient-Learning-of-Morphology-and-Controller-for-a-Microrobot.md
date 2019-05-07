---
layout: post
title: "Data-efficient Learning of Morphology and Controller for a Microrobot"
date: 2019-05-03 18:28:12
categories: arXiv_AI
tags: arXiv_AI Knowledge Optimization
author: Thomas Liao, Grant Wang, Brian Yang, Rene Lee, Kristofer Pister, Sergey Levine, Roberto Calandra
mathjax: true
---

* content
{:toc}

##### Abstract
Robot design is often a slow and difficult process requiring the iterative construction and testing of prototypes, with the goal of sequentially optimizing the design. For most robots, this process is further complicated by the need, when validating the capabilities of the hardware to solve the desired task, to already have an appropriate controller, which is in turn designed and tuned for the specific hardware. In this paper, we propose a novel approach, HPC-BBO, to efficiently and automatically design hardware configurations, and evaluate them by also automatically tuning the corresponding controller. HPC-BBO is based on a hierarchical Bayesian optimization process which iteratively optimizes morphology configurations (based on the performance of the previous designs during the controller learning process) and subsequently learns the corresponding controllers (exploiting the knowledge collected from optimizing for previous morphologies). Moreover, HPC-BBO can select a "batch" of multiple morphology designs at once, thus parallelizing hardware validation and reducing the number of time-consuming production cycles. We validate HPC-BBO on the design of the morphology and controller for a simulated 6-legged microrobot. Experimental results show that HPC-BBO outperforms multiple competitive baselines, and yields a $360\%$ reduction in production cycles over standard Bayesian optimization, thus reducing the hypothetical manufacturing time of our microrobot from 21 to 4 months.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.01334](http://arxiv.org/abs/1905.01334)

##### PDF
[http://arxiv.org/pdf/1905.01334](http://arxiv.org/pdf/1905.01334)

