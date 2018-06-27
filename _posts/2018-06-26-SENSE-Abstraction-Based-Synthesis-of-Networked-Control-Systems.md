---
layout: post
title: "SENSE: Abstraction-Based Synthesis of Networked Control Systems"
date: 2018-06-26 08:53:44
categories: arXiv_RO
tags: arXiv_RO Face
author: Mahmoud Khaled (Technical University of Munich, Munich, Germany), Matthias Rungger (Technical University of Munich, Munich, Germany), Majid Zamani (Technical University of Munich, Munich, Germany)
mathjax: true
---

* content
{:toc}

##### Abstract
While many studies and tools target the basic stabilizability problem of networked control systems (NCS), nowadays modern systems require more sophisticated objectives such as those expressed as formulae in linear temporal logic or as automata on infinite strings. One general technique to achieve this is based on so-called symbolic models, where complex systems are approximated by finite abstractions, and then, correct-by-construction controllers are automatically synthesized for them. We present tool SENSE for the construction of finite abstractions for NCS and the automated synthesis of controllers. Constructed controllers enforce complex specifications over plants in NCS by taking into account several non-idealities of the communication channels. 
 Given a symbolic model of the plant and network parameters, SENSE can efficiently construct a symbolic model of the NCS, by employing operations on binary decision diagrams (BDDs). Then, it synthesizes symbolic controllers satisfying a class of specifications. It has interfaces for the simulation and the visualization of the resulting closed-loop systems using OMNETPP and MATLAB. Additionally, SENSE can generate ready-to-implement VHDL/Verilog or C/C++ codes from the synthesized controllers.

##### Abstract (translated by Google)
虽然许多研究和工具都针对网络控制系统（NCS）的基本稳定性问题，但现代现代系统需要更复杂的目标，例如以线性时间逻辑中的公式表示的那些目标，或无限串上的自动机。实现此目的的一种通用技术是基于所谓的符号模型，其中复杂系统通过有限抽象来近似，然后，针对它们自动合成构建正确的控制器。我们提出了SENSE工具来构建NCS的有限抽象和控制器的自动合成。构建的控制器通过考虑几种不理想的通信渠道，对NCS中的工厂执行复杂的规范。
 给定一个工厂和网络参数的符号模型，SENSE可以通过对二元决策图（BDD）进行操作来高效地构建NCS的符号模型。然后，它综合符合一类规范的符号控制器。它具有用于仿真和使用OMNETPP和MATLAB生成的闭环系统的可视化界面。另外，SENSE可以从综合控制器生成准备实现的VHDL / Verilog或C / C ++代码。

##### URL
[http://arxiv.org/abs/1806.09849](http://arxiv.org/abs/1806.09849)

##### PDF
[http://arxiv.org/pdf/1806.09849](http://arxiv.org/pdf/1806.09849)

