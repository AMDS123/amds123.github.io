---
layout: post
title: "A novel scheme for rapid parallel parameter estimation of gravitational waves from compact binary coalescences"
date: 2015-02-15 22:01:29
categories: arXiv_CV
tags: arXiv_CV
author: C. Pankow, P. Brady, E. Ochsner, R. O'Shaughnessy
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a highly-parallelizable architecture for estimating parameters of compact binary coalescence using gravitational-wave data and waveform models. Using a spherical harmonic mode decomposition, the waveform is expressed as a sum over modes that depend on the intrinsic parameters (e.g. masses) with coefficients that depend on the observer dependent extrinsic parameters (e.g. distance, sky position). The data is then prefiltered against those modes, at fixed intrinsic parameters, enabling efficiently evaluation of the likelihood for generic source positions and orientations, independent of waveform length or generation time. We efficiently parallelize our intrinsic space calculation by integrating over all extrinsic parameters using a Monte Carlo integration strategy. Since the waveform generation and prefiltering happens only once, the cost of integration dominates the procedure. Also, we operate hierarchically, using information from existing gravitational-wave searches to identify the regions of parameter space to emphasize in our sampling. As proof of concept and verification of the result, we have implemented this algorithm using standard time-domain waveforms, processing each event in less than one hour on recent computing hardware. For most events we evaluate the marginalized likelihood (evidence) with statistical errors of less than about 5%, and even smaller in many cases. With a bounded runtime independent of the waveform model starting frequency, a nearly-unchanged strategy could estimate NS-NS parameters in the 2018 advanced LIGO era. Our algorithm is usable with any noise curve and existing time-domain model at any mass, including some waveforms which are computationally costly to evolve.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1502.04370](https://arxiv.org/abs/1502.04370)

##### PDF
[https://arxiv.org/pdf/1502.04370](https://arxiv.org/pdf/1502.04370)

