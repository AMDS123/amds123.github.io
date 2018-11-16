---
layout: post
title: "Stream Reasoning in Temporal Datalog"
date: 2018-11-15 11:06:52
categories: arXiv_AI
tags: arXiv_AI
author: Alessandro Ronca, Mark Kaminski, Bernardo Cuenca Grau, Boris Motik, Ian Horrocks
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, there has been an increasing interest in extending traditional stream processing engines with logical, rule-based, reasoning capabilities. This poses significant theoretical and practical challenges since rules can derive new information and propagate it both towards past and future time points; as a result, streamed query answers can depend on data that has not yet been received, as well as on data that arrived far in the past. Stream reasoning algorithms, however, must be able to stream out query answers as soon as possible, and can only keep a limited number of previous input facts in memory. In this paper, we propose novel reasoning problems to deal with these challenges, and study their computational properties on Datalog extended with a temporal sort and the successor function (a core rule-based language for stream reasoning applications).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1711.04013](http://arxiv.org/abs/1711.04013)

##### PDF
[http://arxiv.org/pdf/1711.04013](http://arxiv.org/pdf/1711.04013)

