---
layout: post
title: "Efficient Multi-objective Neural Architecture Search via Lamarckian Evolution"
date: 2019-02-26 16:06:36
categories: arXiv_CV
tags: arXiv_CV NAS Recognition
author: Thomas Elsken, Jan Hendrik Metzen, Frank Hutter
mathjax: true
---

* content
{:toc}

##### Abstract
Neural Architecture Search aims at automatically finding neural architectures that are competitive with architectures designed by human experts. While recent approaches have achieved state-of-the-art predictive performance for image recognition, they are problematic under resource constraints for two reasons: (1)the neural architectures found are solely optimized for high predictive performance, without penalizing excessive resource consumption, (2) most architecture search methods require vast computational resources. We address the first shortcoming by proposing LEMONADE, an evolutionary algorithm for multi-objective architecture search that allows approximating the entire Pareto-front of architectures under multiple objectives, such as predictive performance and number of parameters, in a single run of the method. We address the second shortcoming by proposing a Lamarckian inheritance mechanism for LEMONADE which generates children networks that are warmstarted with the predictive performance of their trained parents. This is accomplished by using (approximate) network morphism operators for generating children. The combination of these two contributions allows finding models that are on par or even outperform both hand-crafted as well as automatically-designed networks.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1804.09081](https://arxiv.org/abs/1804.09081)

##### PDF
[https://arxiv.org/pdf/1804.09081](https://arxiv.org/pdf/1804.09081)

