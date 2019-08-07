---
layout: post
title: "Bayesian Incremental Inference Update by Re-using Calculations from Belief Space Planning: A New Paradigm"
date: 2019-08-06 08:06:06
categories: arXiv_AI
tags: arXiv_AI Inference Prediction
author: Elad I. Farhi, Vadim Indelman
mathjax: true
---

* content
{:toc}

##### Abstract
Inference and decision making under uncertainty are key processes in every autonomous system and numerous robotic problems. In recent years, the similarities between inference and decision making triggered much work, from developing unified computational frameworks to pondering about the duality between the two. In spite of these efforts, inference and control, as well as inference and belief space planning (BSP) are still treated as two separate processes. In this paper we propose a paradigm shift, a novel approach which deviates from conventional Bayesian inference and utilizes the similarities between inference and BSP. We make the key observation that inference can be efficiently updated using predictions made during the decision making stage, even in light of inconsistent data association between the two. We developed a two staged process that implements our novel approach and updates inference using calculations from the precursory planning phase. Using autonomous navigation in an unknown environment along with iSAM2 efficient methodologies as a test case, we benchmarked our novel approach against standard Bayesian inference, both with synthetic and real-world data (KITTI dataset). Results indicate that not only our approach improves running time by at least a factor of two while providing the same estimation accuracy, but it also alleviates the computational burden of state dimensionality and loop closures.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.02002](http://arxiv.org/abs/1908.02002)

##### PDF
[http://arxiv.org/pdf/1908.02002](http://arxiv.org/pdf/1908.02002)

