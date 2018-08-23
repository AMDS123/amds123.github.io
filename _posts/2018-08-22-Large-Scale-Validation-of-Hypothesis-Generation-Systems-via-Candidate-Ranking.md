---
layout: post
title: "Large-Scale Validation of Hypothesis Generation Systems via Candidate Ranking"
date: 2018-08-22 17:35:22
categories: arXiv_CL
tags: arXiv_CL
author: Justin Sybrandt, Micheal Shtutman, Ilya Safro
mathjax: true
---

* content
{:toc}

##### Abstract
The first step of many research projects is to define and rank a short list of candidates for study. In the modern rapidity of scientific progress, some turn to automated hypothesis generation (HG) systems to aid this process. These systems can identify implicit or overlooked connections within a large scientific corpus, and while their importance grows alongside the pace of science, they lack thorough validation. Without any standard numerical evaluation method, many validate general-purpose HG systems by rediscovering a handful of historical findings, and some wishing to be more thorough may run laboratory experiments based on automatic suggestions. These methods are expensive, time consuming, and cannot scale. Thus, we present a numerical evaluation framework for the purpose of validating HG systems that leverages thousands of validation hypotheses. This method evaluates a HG system by its ability to rank hypotheses by plausibility; a process reminiscent of human candidate selection. Because HG systems do not produce a ranking criteria, specifically those that produce topic models, we additionally present novel metrics to quantify the plausibility of hypotheses given topic model system output. Finally, we demonstrate that our proposed validation method aligns with real-world research goals by deploying our method within Moliere, our recent topic-driven HG system, in order to automatically generate a set of candidate genes related to HIV-associated neurodegenerative disease (HAND). By performing laboratory experiments based on this candidate set, we discover a new connection between HAND and Dead Box RNA Helicase 3 (DDX3). Reproducibility: code, validation data, and results can be found at bit.ly/moliere_validation_repo.

##### Abstract (translated by Google)
许多研究项目的第一步是定义和排列研究候选人名单。在现代科学进步的快速发展中，一些人转向自动假设生成（HG）系统来帮助这一过程。这些系统可以识别大型科学语料库中隐含或被忽视的联系，虽然它们的重要性随着科学的发展而增长，但它们缺乏彻底的验证。没有任何标准的数值评估方法，许多人通过重新发现一些历史发现来验证通用HG系统，而一些希望更彻底的人可以根据自动建议进行实验室实验。这些方法昂贵，耗时且无法扩展。因此，我们提出了一个数值评估框架，用于验证利用数千个验证假设的HG系统。该方法通过合理性对假设进行排序的能力来评估HG系统;一个让人想起人类候选人选择的过程。由于HG系统不产生排名标准，特别是那些产生主题模型的标准，我们还提供了新的度量标准来量化给定主题模型系统输出的假设的合理性。最后，我们通过在我们最近的主题驱动的HG系统Moliere中部署我们的方法来证明我们提出的验证方法符合现实世界的研究目标，以便自动生成一组与HIV相关的神经退行性疾病相关的候选基因（HAND） ）。通过基于该候选组进行实验室实验，我们发现了HAND和Dead Box RNA Helicase 3（DDX3）之间的新联系。再现性：代码，验证数据和结果可以在bit.ly/moliere_validation_repo找到。

##### URL
[http://arxiv.org/abs/1802.03793](http://arxiv.org/abs/1802.03793)

##### PDF
[http://arxiv.org/pdf/1802.03793](http://arxiv.org/pdf/1802.03793)

