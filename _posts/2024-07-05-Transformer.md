---
layout: distill
title: Transformer探賾
date: 2024-07-05
description: 
tags: Transformer
categories: LLM
giscus_comments: false
related_posts: false
related_publications: true
featured: true
images:
  compare: true
  slider: true
toc:
  beginning: true
  sidebar: left

featured: true
authors:
  - name: Wang Yiming
    url: "https://betagi.github.io/"
    affiliations:
      name: Chongqing University, EIE-AI-LAB

bibliography: 2024-06-24-BT_LLM.bib

toc:
  - name: 摘要
citation: true
---

Transformer架构<d-cite key="Vaswani17"></d-cite>的核心是**attention**机制。

# 0. 
让我们回到上世纪70年代末，你还是一名自然语言处理(NLP)工程师，仍然雄心万丈，希望有一天计算机能够如人一般使用和理解语言。

在你小时候，你就开始好奇[Eliza](https://web.njit.edu/~ronkowit/eliza.html)背后的原理，长大后你毅然决定报考计算机来实现你儿时的梦想。课堂上你听着导师讲着[索绪尔](https://literariness.org/2018/03/12/key-theories-of-ferdinand-de-saussure/)、[维特根斯坦](https://arxiv.org/abs/2302.01570)、[乔姆斯基](https://norvig.com/chomsky.html)的名字，你心潮澎拜，感到未来已来。关于语言理论的思考深深影响了你的学术道路，你选择从事基于[专家系统](https://ahistoryofai.com/expert-system/)的机器翻译的研究中，你励志打造一个大而全的基于规则的语法系统，接着来的是AI寒冬，你所在的实验室没有经费支持你继续搞了...那毕业论文怎么办？

你把目光投向导师，这回是一批新的让你似懂非懂的词，“统计学习”、“隐马尔可夫模型”、“贝叶斯”。导师大手一挥，总之就是：
> 用概率统计的思想代替繁琐的句法规则
不考虑语法结构，仅凭借计算条件概率，就能够让机器理解语言？虽然怀疑，但你将信将疑地开始干了，这回是

然而新世纪来的像梦一样，让你感到措手不及，就像[人们说的](https://news.ycombinator.com/item?id=12591834)，“每当一名语言学家被解雇，算法性能就会好一点”，