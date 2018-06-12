---
layout: post
title: "Greybox fuzzing as a contextual bandits problem"
date: 2018-06-11 04:49:00
categories: arXiv_AI
tags: arXiv_AI Detection
author: Ketan Patil, Aditya Kanade
mathjax: true
---

* content
{:toc}

##### Abstract
Greybox fuzzing is one of the most useful and effective techniques for the bug detection in large scale application programs. It uses minimal amount of instrumentation. American Fuzzy Lop (AFL) is a popular coverage based evolutionary greybox fuzzing tool. AFL performs extremely well in fuzz testing large applications and finding critical vulnerabilities, but AFL involves a lot of heuristics while deciding the favored test case(s), skipping test cases during fuzzing, assigning fuzzing iterations to test case(s). In this work, we aim at replacing the heuristics the AFL uses while assigning the fuzzing iterations to a test case during the random fuzzing. We formalize this problem as a `contextual bandit problem' and we propose an algorithm to solve this problem. We have implemented our approach on top of the AFL. We modify the AFL's heuristics with our learned model through the policy gradient method. Our learning algorithm selects the multiplier of the number of fuzzing iterations to be assigned to a test case during random fuzzing, given a fixed length substring of the test case to be fuzzed. We fuzz the substring with this new energy value and continuously updates the policy based upon the interesting test cases it produces on fuzzing.

##### Abstract (translated by Google)
Greybox fuzzing是大规模应用程序中缺陷检测最有用和最有效的技术之一。它使用最少量的仪器。美国模糊Lop（AFL）是一种流行的基于覆盖的进化灰箱模糊工具。 AFL在模糊测试大型应用程序和发现关键漏洞方面表现非常出色，但AFL在决定优先测试用例时会涉及大量启发式技术，在模糊测试期间跳过测试用例，为测试用例分配模糊迭代。在这项工作中，我们旨在取代AFL使用的启发式，同时在随机模糊过程中将模糊迭代分配给测试用例。我们将这个问题形式化为一个“上下文匪问题”，并且我们提出了一个算法来解决这个问题。我们已经在AFL之上实施了我们的方法。我们通过政策梯度法修改AFL的启发式与我们的学习模型。我们的学习算法选择了在随机模糊过程中要分配给测试用例的模糊迭代次数的乘数，假定测试用例的固定长度子串被模糊化。我们用这个新的能量值模糊子串，并根据它在模糊测试中产生的有趣测试案例不断更新策略。

##### URL
[http://arxiv.org/abs/1806.03806](http://arxiv.org/abs/1806.03806)

##### PDF
[http://arxiv.org/pdf/1806.03806](http://arxiv.org/pdf/1806.03806)

