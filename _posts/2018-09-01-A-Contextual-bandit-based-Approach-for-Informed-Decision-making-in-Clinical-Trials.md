---
layout: post
title: "A Contextual-bandit-based Approach for Informed Decision-making in Clinical Trials"
date: 2018-09-01 22:07:23
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Yogatheesan Varatharajah, Brent Berry, Sanmi Koyejo, Ravishankar Iyer
mathjax: true
---

* content
{:toc}

##### Abstract
Clinical trials involving multiple treatments utilize randomization of the treatment assignments to enable the evaluation of treatment efficacies in an unbiased manner. Such evaluation is performed in post hoc studies that usually use supervised-learning methods that rely on large amounts of data collected in a randomized fashion. That approach often proves to be suboptimal in that some participants may suffer and even die as a result of having not received the most appropriate treatments during the trial. Reinforcement-learning methods improve the situation by making it possible to learn the treatment efficacies dynamically during the course of the trial, and to adapt treatment assignments accordingly. Recent efforts using \textit{multi-arm bandits}, a type of reinforcement-learning methods, have focused on maximizing clinical outcomes for a population that was assumed to be homogeneous. However, those approaches have failed to account for the variability among participants that is becoming increasingly evident as a result of recent clinical-trial-based studies. We present a contextual-bandit-based online treatment optimization algorithm that, in choosing treatments for new participants in the study, takes into account not only the maximization of the clinical outcomes but also the patient characteristics. We evaluated our algorithm using a real clinical trial dataset from the International Stroke Trial. The results of our retrospective analysis indicate that the proposed approach performs significantly better than either a random assignment of treatments (the current gold standard) or a multi-arm-bandit-based approach, providing substantial gains in the percentage of participants who are assigned the most suitable treatments. The contextual-bandit and multi-arm bandit approaches provide 72.63% and 64.34% gains, respectively, compared to a random assignment.

##### Abstract (translated by Google)
涉及多种治疗的临床试验利用治疗任务的随机化，以能够以无偏见的方式评估治疗功效。这种评估是在事后研究中进行的，这些研究通常使用依赖于以随机方式收集的大量数据的监督学习方法。这种方法经常被证明是不理想的，因为一些参与者可能会因为在试验期间没有接受最合适的治疗而遭受甚至死亡。强化学习方法通​​过在试验过程中动态学习治疗功效并相应地调整治疗任务来改善情况。最近使用\ textit {multi-arm bandits}（一种强化学习方法）的努力集中于最大化假设为同质的人群的临床结果。然而，由于最近的基于临床试验的研究，这些方法未能解释参与者之间的变化，这种变化正变得越来越明显。我们提出了一种基于情境 - 匪徒的在线治疗优化算法，该研究在为研究中的新参与者选择治疗时，不仅考虑了临床结果的最大化，还考虑了患者的特征。我们使用来自国际卒中试验的真实临床试验数据集评估了我们的算法。我们的回顾性分析结果表明，所提出的方法比随机分配治疗（当前的黄金标准）或基于多臂匪提的方法表现更好，从而大大提高了被分配治疗的参与者的百分比。最合适的治疗方法与随机分配相比，情境强盗和多臂强盗方法分别提供72.63％和64.34％的增益。

##### URL
[http://arxiv.org/abs/1809.00258](http://arxiv.org/abs/1809.00258)

##### PDF
[http://arxiv.org/pdf/1809.00258](http://arxiv.org/pdf/1809.00258)

