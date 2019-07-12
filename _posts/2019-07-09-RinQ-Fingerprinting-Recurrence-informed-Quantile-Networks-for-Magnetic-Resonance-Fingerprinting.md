---
layout: post
title: "RinQ Fingerprinting: Recurrence-informed Quantile Networks for Magnetic Resonance Fingerprinting"
date: 2019-07-09 10:29:55
categories: arXiv_CV
tags: arXiv_CV RNN Deep_Learning Quantitative
author: Elisabeth Hoppe (1), Florian Thamm (1), Gregor K&#xf6;rzd&#xf6;rfer (2), Christopher Syben (1), Franziska Schirrmacher (1), Mathias Nittka (2), Josef Pfeuffer (2), Heiko Meyer (2), Andreas Maier (1) ((1) Pattern Recognition Lab, Department of Computer Science, Friedrich-Alexander-Universit&#xe4;t Erlangen-N&#xfc;rnberg, Erlangen, Germany, (2) MR Application Development, Siemens Healthcare, Erlangen, Germany)
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, Magnetic Resonance Fingerprinting (MRF) was proposed as a quantitative imaging technique for the simultaneous acquisition of tissue parameters such as relaxation times $T_1$ and $T_2$. Although the acquisition is highly accelerated, the state-of-the-art reconstruction suffers from long computation times: Template matching methods are used to find the most similar signal to the measured one by comparing it to pre-simulated signals of possible parameter combinations in a discretized dictionary. Deep learning approaches can overcome this limitation, by providing the direct mapping from the measured signal to the underlying parameters by one forward pass through a network. In this work, we propose a Recurrent Neural Network (RNN) architecture in combination with a novel quantile layer. RNNs are well suited for the processing of time-dependent signals and the quantile layer helps to overcome the noisy outliers by considering the spatial neighbors of the signal. We evaluate our approach using in-vivo data from multiple brain slices and several volunteers, running various experiments. We show that the RNN approach with small patches of complex-valued input signals in combination with a quantile layer outperforms other architectures, e.g. previously proposed CNNs for the MRF reconstruction reducing the error in $T_1$ and $T_2$ by more than 80%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05277](http://arxiv.org/abs/1907.05277)

##### PDF
[http://arxiv.org/pdf/1907.05277](http://arxiv.org/pdf/1907.05277)

