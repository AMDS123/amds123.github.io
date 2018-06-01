---
layout: post
title: "Deep Reinforcement Learning for De-Novo Drug Design"
date: 2018-05-31 17:13:56
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Mariya Popova, Olexandr Isayev, Alexander Tropsha
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel computational strategy for de novo design of molecules with desired properties termed ReLeaSE (Reinforcement Learning for Structural Evolution). Based on deep and reinforcement learning approaches, ReLeaSE integrates two deep neural networks - generative and predictive - that are trained separately but employed jointly to generate novel targeted chemical libraries. ReLeaSE employs simple representation of molecules by their SMILES strings only. Generative models are trained with stack-augmented memory network to produce chemically feasible SMILES strings, and predictive models are derived to forecast the desired properties of the de novo generated compounds. In the first phase of the method, generative and predictive models are trained separately with a supervised learning algorithm. In the second phase, both models are trained jointly with the reinforcement learning approach to bias the generation of new chemical structures towards those with the desired physical and/or biological properties. In the proof-of-concept study, we have employed the ReLeaSE method to design chemical libraries with a bias toward structural complexity or biased toward compounds with either maximal, minimal, or specific range of physical properties such as melting point or hydrophobicity, as well as to develop novel putative inhibitors of JAK2. The approach proposed herein can find a general use for generating targeted chemical libraries of novel compounds optimized for either a single desired property or multiple properties.

##### Abstract (translated by Google)
我们提出了一种新的计算策略，用于从头设计具有期望特性的分子，称为ReLeaSE（用于结构进化的增强学习）。基于深度和强化学习方法，ReLeaSE集成了两个深度神经网络 - 生成性和预测性 - 分别进行训练，但共同用于生成新型靶向化学文库。 ReLeaSE只用SMILES字符串简单表示分子。生成模型通过堆栈增强的内存网络进行训练以生成化学上可行的SMILES字符串，并导出预测模型以预测从头生成的化合物的期望属性。在该方法的第一阶段，生成和预测模型分别用监督学习算法训练。在第二阶段，两种模式都与强化学习方法一起训练，以将新化学结构的产生偏向具有所需物理和/或生物特性的那些结构。在概念验证研究中，我们采用了ReLeaSE方法来设计化学文库，以偏向于结构复杂性，或者偏向于具有最大，最小或特定物理性质范围（如熔点或疏水性）的化合物以开发新型推定的JAK2抑制剂。本文提出的方法可以找到用于产生针对单个期望性质或多个性质优化的新型化合物的靶向化学文库的一般用途。

##### URL
[http://arxiv.org/abs/1711.10907](http://arxiv.org/abs/1711.10907)

##### PDF
[http://arxiv.org/pdf/1711.10907](http://arxiv.org/pdf/1711.10907)

