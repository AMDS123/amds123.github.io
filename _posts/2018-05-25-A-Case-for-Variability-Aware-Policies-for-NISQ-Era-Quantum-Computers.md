---
layout: post
title: "A Case for Variability-Aware Policies for NISQ-Era Quantum Computers"
date: 2018-05-25 16:09:16
categories: arXiv_CV
tags: arXiv_CV QA VQA
author: Swamit S. Tannu, Moinuddin K.Qureshi
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, IBM, Google, and Intel showcased quantum computers ranging from 49 to 72 qubits. While these systems represent a significant milestone in the advancement of quantum computing, existing and near-term quantum computers are not yet large enough to fully support quantum error-correction. Such systems with few tens to few hundreds of qubits are termed as Noisy Intermediate Scale Quantum computers (NISQ), and these systems can provide benefits for a class of quantum algorithms. In this paper, we study the problems of Qubit-Allocation (mapping of program qubits to machine qubits) and Qubit-Movement(routing qubits from one location to another to perform entanglement). We observe that there exists variation in the error rates of different qubits and links, which can have an impact on the decisions for qubit movement and qubit allocation. We analyze characterization data for the IBM-Q20 quantum computer gathered over 52 days to understand and quantify the variation in the error-rates and find that there is indeed significant variability in the error rates of the qubits and the links connecting them. We define reliability metrics for NISQ computers and show that the device variability has the substantial impact on the overall system reliability. To exploit the variability in error rate, we propose Variation-Aware Qubit Movement (VQM) and Variation-Aware Qubit Allocation (VQA), policies that optimize the movement and allocation of qubits to avoid the weaker qubits and links and guide more operations towards the stronger qubits and links. We show that our Variation-Aware policies improve the reliability of the NISQ system up to 2.5x.

##### Abstract (translated by Google)
最近，IBM，Google和英特尔展示了量子计算机，其量程从49到72个。虽然这些系统是量子计算发展的重要里程碑，但现有的和近期的量子计算机还不足以完全支持量子纠错。具有几十到几百个量子位的这种系统被称为噪声中间量子量子计算机（NISQ），并且这些系统可以为一类量子算法提供益处。在本文中，我们研究了Qubit分配（程序量子比特到机器量子比特的映射）和量子比特运动（将量子比特从一个位置路由到另一个执行纠缠）的问题。我们观察到不同量子比特和链路的差错率存在变化，这会对量子比特移动和量子比特分配的决定产生影响。我们分析了52天收集的IBM-Q20量子计算机的表征数据，以了解和量化误差率的变化，并发现量子比特和连接它们的链路的误差率确实存在显着的变化。我们为NISQ计算机定义可靠性指标，并显示设备可变性对整体系统可靠性有重大影响。为了利用差错率的变化，我们提出了变异感知的Qubit运动（VQM）和变异感知的Qubit分配（VQA），这些策略优化了量子比特的移动和分配，以避免较弱的量子比特和链路，并指导更多的操作更强的量子比特和链接。我们表明，我们的变化感知政策可将NISQ系统的可靠性提高至2.5倍。

##### URL
[https://arxiv.org/abs/1805.10224](https://arxiv.org/abs/1805.10224)

##### PDF
[https://arxiv.org/pdf/1805.10224](https://arxiv.org/pdf/1805.10224)

