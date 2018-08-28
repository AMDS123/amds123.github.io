---
layout: post
title: "Adaptive Grey-Box Fuzz-Testing with Thompson Sampling"
date: 2018-08-24 18:22:46
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Siddharth Karamcheti, Gideon Mann, David Rosenberg
mathjax: true
---

* content
{:toc}

##### Abstract
Fuzz testing, or "fuzzing," refers to a widely deployed class of techniques for testing programs by generating a set of inputs for the express purpose of finding bugs and identifying security flaws. Grey-box fuzzing, the most popular fuzzing strategy, combines light program instrumentation with a data driven process to generate new program inputs. In this work, we present a machine learning approach that builds on AFL, the preeminent grey-box fuzzer, by adaptively learning a probability distribution over its mutation operators on a program-specific basis. These operators, which are selected uniformly at random in AFL and mutational fuzzers in general, dictate how new inputs are generated, a core part of the fuzzer's efficacy. Our main contributions are two-fold: First, we show that a sampling distribution over mutation operators estimated from training programs can significantly improve performance of AFL. Second, we introduce a Thompson Sampling, bandit-based optimization approach that fine-tunes the mutator distribution adaptively, during the course of fuzzing an individual program. A set of experiments across complex programs demonstrates that tuning the mutational operator distribution generates sets of inputs that yield significantly higher code coverage and finds more crashes faster and more reliably than both baseline versions of AFL as well as other AFL-based learning approaches.

##### Abstract (translated by Google)
模糊测试或“模糊测试”是指广泛部署的一类技术，用于通过生成一组输入来测试程序，以明确查找错误和识别安全漏洞。灰盒模糊测试是最流行的模糊测试策略，它将轻型程序设备与数据驱动过程相结合，以生成新的程序输入。在这项工作中，我们提出了一种机器学习方法，它建立在AFL（一种卓越的灰盒模糊器）之上，通过在特定程序的基础上自适应地学习其变异算子的概率分布。这些算子在AFL和突变模糊器中随机均匀选择，决定了新输入是如何产生的，这是模糊器功效的核心部分。我们的主要贡献是双重的：首先，我们表明从训练计划中估计的变异算子的采样分布可以显着提高AFL的性能。其次，我们介绍了一种基于强盗的Thompson Sampling优化方法，该方法可以在模糊单个程序的过程中自适应地调整mutator分布。跨越复杂程序的一组实验表明，调整突变运算符分布会生成一组输入，这些输入可以产生更高的代码覆盖率，并且比基线版本的AFL以及其他基于AFL的学习方法更快，更可靠地发现崩溃。

##### URL
[http://arxiv.org/abs/1808.08256](http://arxiv.org/abs/1808.08256)

##### PDF
[http://arxiv.org/pdf/1808.08256](http://arxiv.org/pdf/1808.08256)

