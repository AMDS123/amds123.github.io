---
layout: post
title: "Generating Plans that Predict Themselves"
date: 2018-02-14 18:20:19
categories: arXiv_AI
tags: arXiv_AI
author: Jaime F. Fisac, Chang Liu, Jessica B. Hamrick, S. Shankar Sastry, J. Karl Hedrick, Thomas L. Griffiths, Anca D. Dragan
mathjax: true
---

* content
{:toc}

##### Abstract
Collaboration requires coordination, and we coordinate by anticipating our teammates' future actions and adapting to their plan. In some cases, our teammates' actions early on can give us a clear idea of what the remainder of their plan is, i.e. what action sequence we should expect. In others, they might leave us less confident, or even lead us to the wrong conclusion. Our goal is for robot actions to fall in the first category: we want to enable robots to select their actions in such a way that human collaborators can easily use them to correctly anticipate what will follow. While previous work has focused on finding initial plans that convey a set goal, here we focus on finding two portions of a plan such that the initial portion conveys the final one. We introduce $t$-\ACty{}: a measure that quantifies the accuracy and confidence with which human observers can predict the remaining robot plan from the overall task goal and the observed initial $t$ actions in the plan. We contribute a method for generating $t$-predictable plans: we search for a full plan that accomplishes the task, but in which the first $t$ actions make it as easy as possible to infer the remaining ones. The result is often different from the most efficient plan, in which the initial actions might leave a lot of ambiguity as to how the task will be completed. Through an online experiment and an in-person user study with physical robots, we find that our approach outperforms a traditional efficiency-based planner in objective and subjective collaboration metrics.

##### Abstract (translated by Google)
合作需要协调，我们通过预测我们的队友未来的行动并适应他们的计划进行协调。在某些情况下，我们队友的早期行动可以让我们清楚地知道他们计划的其余部分，即我们应该期待什么样的行动顺序。在另一些情况下，他们可能会让我们失去信心，甚至导致我们得出错误的结论。我们的目标是让机器人行动落入第一类：我们希望使机器人能够以这样一种方式选择他们的行为，即人类合作者可以轻松地使用它们来正确预测随后会发生的事情。虽然以前的工作集中在寻找传达既定目标的初始计划，但我们在此着重于找出计划的两个部分，以便最初部分传达最终计划。我们引入$ t $  -  \ ACty {}：量化人类观察者从总体任务目标和观察到的初始$ t $行动中预测剩余机器人计划的准确性和置信度的度量。我们提供了一种生成$ t $ -predictable计划的方法：我们搜索完成任务的完整计划，但是其中第一个$ t $操作可以尽可能简单地推断剩余计划。其结果往往不同于最有效的计划，在这种计划中，最初的行动可能会给如何完成任务留下很多模糊之处。通过在线实验和使用物理机器人进行面对面用户研究，我们发现，我们的方法在客观和主观协作指标上优于传统效率计划。

##### URL
[http://arxiv.org/abs/1802.05250](http://arxiv.org/abs/1802.05250)

##### PDF
[http://arxiv.org/pdf/1802.05250](http://arxiv.org/pdf/1802.05250)

