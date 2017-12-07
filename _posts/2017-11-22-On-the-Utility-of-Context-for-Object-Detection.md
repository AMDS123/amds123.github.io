---
layout: post
title: "On the Utility of Context for Object Detection"
date: 2017-11-22 17:54:22
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Ehud Barnea, Ohad Ben-Shahar
mathjax: true
---

* content
{:toc}

##### Abstract
The recurring context in which objects appear holds valuable information that can be employed to predict their existence. This intuitive observation indeed led many researchers to endow appearance-based detectors with explicit reasoning about context. The underlying thesis suggests that with stronger contextual relations, the better improvement in detection capacity one can expect from such a combined approach. In practice, however, the observed improvement in many case is modest at best, and often only marginal. In this work we seek to understand this phenomenon better, in part by pursuing an opposite approach. Instead of going from context to detection score, we formulate the score as a function of standard detector results and contextual relations, an approach that allows to treat the utility of context as an optimization problem in order to obtain the largest gain possible from considering context in the first place. Analyzing different contextual relations reveals the most helpful ones and shows that in many cases including context can help while in other cases a significant improvement is simply impossible or impractical. To better understand these results we then analyze the ability of context to handle different types of false detections, revealing that contextual information cannot ameliorate localization errors, which in turn also diminish the observed improvement obtained by correcting other types of errors. These insights provide further explanations and better understanding regarding the success or failure of utilizing context for object detection.

##### Abstract (translated by Google)
对象出现的反复出现的上下文保存着有价值的信息，可以用来预测它们的存在。这种直观的观察确实导致了许多研究人员赋予基于外观的探测器上下文的明确推理。底层的论文表明，在更强的背景关系下，人们可以从这样的综合方法中获得更好的检测能力的提高。然而，在实践中，在许多情况下，所观察到的改善最多只是适度的，而且往往只是边际。在这项工作中，我们试图更好地理解这个现象，部分是通过追求相反的方法。我们不是从上下文到检测分数，而是将分数表示为标准检测器结果和上下文关系的函数，这种方法允许将上下文的效用作为优化问题来处理，以便从考虑上下文获得最大的收益第一个地方。分析不同的上下文关系揭示了最有帮助的关系，并且表明，在许多情况下，包括上下文可以提供帮助，而在其他情况下，显着改进根本不可能或不切实际。为了更好地理解这些结果，我们分析了上下文处理不同类型的错误检测的能力，揭示了上下文信息不能改善本地化错误，这反过来也减少了通过纠正其他类型的错误而获得的观察到的改善。这些见解提供了进一步的解释和更好地理解利用上下文进行对象检测的成功或失败。

##### URL
[https://arxiv.org/abs/1711.05471](https://arxiv.org/abs/1711.05471)

##### PDF
[https://arxiv.org/pdf/1711.05471](https://arxiv.org/pdf/1711.05471)

