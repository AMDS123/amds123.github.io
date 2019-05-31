---
layout: post
title: "Memory-Driven Mixed Low Precision Quantization For Enabling Deep Network Inference On Microcontrollers"
date: 2019-05-30 14:50:42
categories: arXiv_CV
tags: arXiv_CV Inference
author: Manuele Rusci, Alessandro Capotondi, Luca Benini
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel end-to-end methodology for enabling the deployment of low-error deep networks on microcontrollers. To fit the memory and computational limitations of resource-constrained edge-devices, we exploit mixed low-bitwidth compression, featuring 8, 4 or 2-bit uniform quantization, and we model the inference graph with integer-only operations. Our approach aims at determining the minimum bit precision of every activation and weight tensor given the memory constraints of a device. This is achieved through a rule-based iterative procedure, which cuts the number of bits of the most memory-demanding layers, aiming at meeting the memory constraints. After a quantization-aware retraining step, the fake-quantized graph is converted into an inference integer-only model by inserting the Integer Channel-Normalization (ICN) layers, which introduce a negligible loss as demonstrated on INT4 MobilenetV1 models. We report the latency-accuracy evaluation of mixed-precision MobilenetV1 family networks on a STM32H7 microcontroller. Our experimental results demonstrate an end-to-end deployment of an integer-only Mobilenet network with Top1 accuracy of 68% on a device with only 2MB of FLASH memory and 512kB of RAM, improving by 8% the Top1 accuracy with respect to previously published 8 bit implementations for microcontrollers.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.13082](https://arxiv.org/abs/1905.13082)

##### PDF
[https://arxiv.org/pdf/1905.13082](https://arxiv.org/pdf/1905.13082)

