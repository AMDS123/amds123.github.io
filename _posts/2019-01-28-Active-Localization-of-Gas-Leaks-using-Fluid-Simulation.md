---
layout: post
title: "Active Localization of Gas Leaks using Fluid Simulation"
date: 2019-01-28 11:26:49
categories: arXiv_RO
tags: arXiv_RO Inference
author: Martin Asenov, Marius Rutkauskas, Derryck Reid, Kartic Subr, Subramanian Ramamoorthy
mathjax: true
---

* content
{:toc}

##### Abstract
Sensors are routinely mounted on robots to acquire various forms of measurements in spatio-temporal fields. Locating features within these fields and reconstruction (mapping) of the dense fields can be challenging in resource-constrained situations, such as when trying to locate the source of a gas leak from a small number of measurements. In such cases, a model of the underlying complex dynamics can be exploited to discover informative paths within the field. We use a fluid simulator as a model, to guide inference for the location of a gas leak. We perform localization via minimization of the discrepancy between observed measurements and gas concentrations predicted by the simulator. Our method is able to account for dynamically varying parameters of wind flow (e.g., direction and strength), and its effects on the observed distribution of gas. We develop algorithms for off-line inference as well as for on-line path discovery via active sensing. We demonstrate the efficiency, accuracy and versatility of our algorithm using experiments with a physical robot conducted in outdoor environments. We deploy an unmanned air vehicle (UAV) mounted with a CO2 sensor to automatically seek out a gas cylinder emitting CO2 via a nozzle. We evaluate the accuracy of our algorithm by measuring the error in the inferred location of the nozzle, based on which we show that our proposed approach is competitive with respect to state of the art baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.09608](http://arxiv.org/abs/1901.09608)

##### PDF
[http://arxiv.org/pdf/1901.09608](http://arxiv.org/pdf/1901.09608)

