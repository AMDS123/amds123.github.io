---
layout: post
title: "Tactics to Directly Map CNN graphs on Embedded FPGAs"
date: 2017-11-20 08:13:39
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Kamel Abdelouahab (IP), Maxime Pelcat (IETR), Jocelyn Sérot (IP), Cédric Bourrasset (IP), François Berry (IP), Jocelyn Serot (LASMEA)
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Convolutional Neural Networks (CNNs) are the state-of-the-art in image classification. Since CNN feed forward propagation involves highly regular parallel computation, it benefits from a significant speed-up when running on fine grain parallel programmable logic devices. As a consequence, several studies have proposed FPGA-based accelerators for CNNs. However, because of the large computationalpower required by CNNs, none of the previous studies has proposed a direct mapping of the CNN onto the physical resources of an FPGA, allocating each processing actor to its own hardware instance.In this paper, we demonstrate the feasibility of the so called direct hardware mapping (DHM) and discuss several tactics we explore to make DHM usable in practice. As a proof of concept, we introduce the HADDOC2 open source tool, that automatically transforms a CNN description into a synthesizable hardware description with platform-independent direct hardware mapping.

##### Abstract (translated by Google)
深度卷积神经网络（CNN）是图像分类中的最新技术。由于CNN前馈传播涉及高度规则的并行计算，因此在细粒度并行可编程逻辑器件上运行时，其显着加速将受益。因此，有几项研究提出了基于FPGA的CNN加速器。但是，由于CNN所需要的计算能力很大，以前的研究都没有提出将CNN直接映射到FPGA的物理资源上，将每个处理参与者分配给自己的硬件实例。本文证明了可行性所谓的直接硬件映射（DHM），并讨论了我们探索使DHM在实践中可用的几种策略。作为一个概念证明，我们介绍HADDOC2开源工具，该工具将CNN描述自动转换为可独立进行平台无关硬件映射的可综合硬件描述。

##### URL
[https://arxiv.org/abs/1712.04322](https://arxiv.org/abs/1712.04322)

##### PDF
[https://arxiv.org/pdf/1712.04322](https://arxiv.org/pdf/1712.04322)

