---
layout: post
title: "Multi-shot ASP solving with clingo"
date: 2018-03-20 16:43:53
categories: arXiv_AI
tags: arXiv_AI Face Optimization
author: Martin Gebser, Roland Kaminski, Benjamin Kaufmann, Torsten Schaub
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a new flexible paradigm of grounding and solving in Answer Set Programming (ASP), which we refer to as multi-shot ASP solving, and present its implementation in the ASP system clingo. 
 Multi-shot ASP solving features grounding and solving processes that deal with continuously changing logic programs. In doing so, they remain operative and accommodate changes in a seamless way. For instance, such processes allow for advanced forms of search, as in optimization or theory solving, or interaction with an environment, as in robotics or query-answering. Common to them is that the problem specification evolves during the reasoning process, either because data or constraints are added, deleted, or replaced. This evolutionary aspect adds another dimension to ASP since it brings about state changing operations. We address this issue by providing an operational semantics that characterizes grounding and solving processes in multi-shot ASP solving. This characterization provides a semantic account of grounder and solver states along with the operations manipulating them. 
 The operative nature of multi-shot solving avoids redundancies in relaunching grounder and solver programs and benefits from the solver's learning capacities. clingo accomplishes this by complementing ASP's declarative input language with control capacities. On the declarative side, a new directive allows for structuring logic programs into named and parameterizable subprograms. The grounding and integration of these subprograms into the solving process is completely modular and fully controllable from the procedural side. To this end, clingo offers a new application programming interface that is conveniently accessible via scripting languages.

##### Abstract (translated by Google)
我们引入了一种新的灵活的基础和解决方案，在我们称之为多重ASP解决方案的答案集编程（ASP）中，并将其实现应用于ASP系统中。
 多重ASP解决方案的特色在于处理不断变化的逻辑程序的接地和求解过程。在这样做的时候，他们仍然可以运作，并以无缝方式适应变化。例如，这些过程允许进行高级形式的搜索，如在优化或理论解决中，或者与机器人或查询回答中的环境交互。他们通常认为问题规范在推理过程中会发生演变，或者是因为数据或约束被添加，删除或替换。这个演化方面增加了ASP的另一个层面，因为它带来了状态变化操作。我们通过提供一种操作语义来解决这个问题，该操作语义描述了多重ASP解决方案中的基础和求解过程。这种表征提供了一个语义帐号的地滚球和解算器状态以及操作它们的操作。
 多次求解的操作性避免了重新启动地滚球和求解程序以及解算器学习能力带来的好处。 clingo通过用控制能力补充ASP的声明性输入语言来实现这一点。在声明方面，一个新的指令允许将逻辑程序构造成命名和可参数化的子程序。这些子程序的基础和整合到求解过程中是完全模块化的，并且可以从程序方面完全控制。为此，clingo提供了一个新的应用程序编程接口，可以通过脚本语言方便地访问。

##### URL
[http://arxiv.org/abs/1705.09811](http://arxiv.org/abs/1705.09811)

##### PDF
[http://arxiv.org/pdf/1705.09811](http://arxiv.org/pdf/1705.09811)

