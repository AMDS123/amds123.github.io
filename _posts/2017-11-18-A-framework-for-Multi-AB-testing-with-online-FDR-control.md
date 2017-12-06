---
layout: post
title: "A framework for Multi-A/B testing with online FDR control"
date: 2017-11-18 07:25:12
categories: arXiv_CV
tags: arXiv_CV Caption
author: Fanny Yang, Aaditya Ramdas, Kevin Jamieson, Martin J. Wainwright
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an alternative framework to existing setups for controlling false alarms when multiple A/B tests are run over time. This setup arises in many practical applications, e.g. when pharmaceutical companies test new treatment options against control pills for different diseases, or when internet companies test their default webpages versus various alternatives over time. Our framework proposes to replace a sequence of A/B tests by a sequence of best-arm MAB instances, which can be continuously monitored by the data scientist. When interleaving the MAB tests with an an online false discovery rate (FDR) algorithm, we can obtain the best of both worlds: low sample complexity and any time online FDR control. Our main contributions are: (i) to propose reasonable definitions of a null hypothesis for MAB instances; (ii) to demonstrate how one can derive an always-valid sequential p-value that allows continuous monitoring of each MAB test; and (iii) to show that using rejection thresholds of online-FDR algorithms as the confidence levels for the MAB algorithms results in both sample-optimality, high power and low FDR at any point in time. We run extensive simulations to verify our claims, and also report results on real data collected from the New Yorker Cartoon Caption contest.

##### Abstract (translated by Google)
我们建议现有设置的替代框架，以便在多个A / B测试随时间运行时控制误报。这种设置出现在许多实际应用中，例如当制药公司测试针对不同疾病的控制药丸的新的治疗选择，或者当互联网公司测试他们的默认网页与随着时间推移的各种替代方案。我们的框架提出用一系列最好的MAB实例代替一系列A / B测试，这些实例可以由数据科学家连续监测。当MAB测试与在线错误发现率（FDR）算法交错时，我们可以获得最好的结果：低样本复杂度和任何在线FDR控制。我们的主要贡献是：（i）为MAB实例提出合理的零假设定义; （ii）展示如何推导出始终有效的连续p值，以便连续监测每个MAB测试; （iii）显示使用在线-FDR算法的拒绝阈值作为MAB算法的置信度水平在任何时间点都导致样本最优性，高功率和低FDR。我们运行大量的模拟来验证我们的说法，并且报告从纽约人卡通字幕比赛收集的真实数据的结果。

##### URL
[https://arxiv.org/abs/1706.05378](https://arxiv.org/abs/1706.05378)

