---
layout: post
title: "OptStream: Releasing Time Series Privately"
date: 2018-10-30 13:24:03
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Ferdinando Fioretto, Pascal Van Hentenryck
mathjax: true
---

* content
{:toc}

##### Abstract
Many applications of machine learning and optimization operate on data streams. While these datasets are fundamental to fuel decision-making algorithms, often they contain sensitive information about individuals and their usage poses significant privacy risks. Motivated by an application in energy systems, this paper presents OPTSTREAM, a novel algorithm for releasing differentially private data streams under the w-event model of privacy. OPTSTREAM is a 4-step procedure consisting of sampling, perturbation, reconstruction, and post-processing modules. First, the sampling module selects a small set of points to access in each period of interest. Then, the perturbation module adds noise to the sampled data points to guarantee privacy. Next, the reconstruction module reassembles non-sampled data points from the perturbed sample points. Finally, the post-processing module uses convex optimization over the private output of the previous modules, as well as the private answers of additional queries on the data stream, to improve accuracy by redistributing the added noise. OPTSTREAM is evaluated on a test case involving the release of a real data stream from the largest European transmission operator. Experimental results show that OPTSTREAM may not only improve the accuracy of state-of-the-art methods by at least one order of magnitude but also supports accurate load forecasting on the private data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1808.01949](http://arxiv.org/abs/1808.01949)

##### PDF
[http://arxiv.org/pdf/1808.01949](http://arxiv.org/pdf/1808.01949)

