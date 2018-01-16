---
layout: post
title: "Fairness in Supervised Learning: An Information Theoretic Approach"
date: 2018-01-13 04:03:04
categories: arXiv_AI
tags: arXiv_AI Prediction
author: AmirEmad Ghassami, Sajad Khodadadian, Negar Kiyavash
mathjax: true
---

* content
{:toc}

##### Abstract
Automated decision making systems are increasingly being used in real-world applications. In these systems for the most part, the decision rules are derived by minimizing the training error on the available historical data. Therefore, if there is a bias related to a sensitive attribute such as gender, race, religion, etc. in the data, say, due to cultural/historical discriminatory practices against a certain demographic, the system could continue discrimination in decisions by including the said bias in its decision rule. We present an information theoretic framework for designing fair predictors from data, which aim to prevent discrimination against a specified sensitive attribute in a supervised learning setting. We use equalized odds as the criterion for discrimination, which demands that the prediction should be independent of the protected attribute conditioned on the actual label. To ensure fairness and generalization simultaneously, we compress the data to an auxiliary variable, which is used for the prediction task. This auxiliary variable is chosen such that it is decontaminated from the discriminatory attribute in the sense of equalized odds. The final predictor is obtained by applying a Bayesian decision rule to the auxiliary variable.

##### Abstract (translated by Google)
自动决策系统越来越多地被用于实际应用。在大多数这些系统中，决策规则是通过最小化可用历史数据上的训练错误而得出的。因此，如果数据中存在与性别，种族，宗教信仰等敏感属性有关的偏见，例如由于针对某一人口的文化/历史歧视做法，该制度可能会继续通过将说其决定规则的偏见。我们提出一个从数据设计公平预测的信息理论框架，旨在防止在监督学习环境中对特定敏感属性的歧视。我们使用均衡赔率作为判别标准，这要求预测应该独立于受实际标签限制的受保护属性。为了保证公平性和一致性，我们将数据压缩成一个辅助变量，用于预测任务。这个辅助变量被选择为使得它在均衡赔率的意义上从歧视性属性中被净化。通过对辅助变量应用贝叶斯决策规则来获得最终的预测器。

##### URL
[https://arxiv.org/abs/1801.04378](https://arxiv.org/abs/1801.04378)

##### PDF
[https://arxiv.org/pdf/1801.04378](https://arxiv.org/pdf/1801.04378)

