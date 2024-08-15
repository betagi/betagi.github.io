---
layout: post
title: The Brief History and Evolution of Artificial Intelligence
date: 2024-05-28
description: Grasping the history and evolution of AI is crucial as it offers a roadmap to the origins and influence of LLMs. 
tags: LLM AI history
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
citation: true
---


The following content aims to provide a broader perspective, thereby enhancing readers’ understanding of the historical background of my [thesis]().  To achieve this, this additional post delves into the rich history of AI's progression and delivers a brief description. The contents below are mainly derived from and inspired by Russell et al.{% cite Russell10 %}

### The Birth of Artificial Intelligence (1943-1956)
The genesis of AI can be traced back to 1943 when Warren McCulloch and Walter Pitts laid the foundation with their pioneering work. They created a model of artificial neurons based on three sources of inspiration: the physiological knowledge of brain neurons, the formal [analysis](https://en.wikipedia.org/wiki/Principia_Mathematica) of propositional logic by Russell and Whitehead, and Turing's [theory of computation](https://www.alanturing.net/turing_archive/pages/Reference%20Articles/BriefHistofComp.html). Their model featured neurons that were either "on" or "off" and would switch "on" when stimulated by a specific amount of adjacent neurons. They demonstrated that any computable function could be computed by networks of such neurons, which could also perform logical operations like AND, OR, and NOT.

In the 1940s and 1950s, Alan Turing, a mathematician and logician, invented the Turing machine, which can simulate any algorithm. Turing proposed the Turing Test to determine if a machine possesses _human-like_ intelligence. He argued that if the judges could not distinguish between responses from the candidates of _intelligent agents_ during a conversation, the machine could be considered _intelligent_. This test inspired AI research, leading to the development of subfields such as machine perception, learning, language processing, memory, and decision-making. 

In 1949, Canadian psychologist Donald Hebb introduced Hebbian learning, a theory of synaptic plasticity that became fundamental to neural network learning. His principle, often summarized as "neurons that fire together wire together," laid the groundwork for the idea that weight changes in neural connections are proportional to the product of activation values.

In 1950, Marvin Minsky and Dean Edmonds built the first neural network computer, the SNARC, which simulated a network of 40 neurons. This was followed by further research into neural networks and computational theories.

In 1955, John McCarthy, along with Marvin Minsky, Claude Shannon, and Nathaniel Rochester, organized a workshop at Dartmouth College in 1956. This event is considered the official birth of AI as a distinct discipline. The attendees aimed to create machines capable of simulating human cognitive abilities, leading to the first use of the term "artificial intelligence." McCarthy preferred "AI" over terms like "computational rationality" despite potential misconceptions, to differentiate it from Norbert Wiener's analog cybernetic devices.

### The Golden Age of AI (1956-1974)
After the meeting of Dartmouth, the enthusiasm for AI soared, marking the golden age of AI research. Early researchers developed intelligent systems based on human experiences, logic, and induction. Notable achievements included the development of the first AI programming languages (IPL, LISP), Arthur Samuel's checkers program, and Allen Newell and Herbert Simon's _General Problem Solver_ {% cite GPS %}. Institutions like MIT and Stanford established AI labs, leading to exponential growth in AI research funding.

In 1957, Newell and Simon introduced the GPS, designed to mimic human problem-solving. Their success led to the physical symbol system hypothesis, suggesting that any intelligent system must operate by manipulating symbolic data structures. In 1958, John McCarthy made two major contributions: defining the LISP programming language, which became pivotal for AI, and proposing the concept of the "advice taker", a program that could reason using general knowledge.

### AI Winter (1974-1980, 1987-1993)
Despite early successes, AI research faced setbacks due to technological limitations, insufficient computational power, and funding cuts. These periods, known as "AI winters", saw a shift in focus toward specialized AI applications, laying the groundwork for future advancements.


### The Rise of Connectionism, Neural Networks, and Probabilistic Reasoning (1982-2000)
In 1982, John Hopfield's theoretical models {% cite Hopfield82 %}  for self-organization and memory revitalized neural network research. The rediscovery of the _backpropagation_ {% cite back-propagation %}  algorithm in the mid-1980s further propelled connectionism, enabling significant advancements in pattern recognition and natural language processing. Researchers like Terrence Sejnowski, Geoffrey Hinton, and David Rumelhart expanded the field through their work on Boltzmann machines and backpropagation.

Simultaneously, the limitations of expert systems led to the rise of probabilistic reasoning and machine learning. Judea Pearl's Bayesian networks and Richard Sutton's reinforcement learning integrated probability theory with decision-making, providing robust frameworks for AI applications across various domains.

### The Era of Big Data and the Deep Learning Revolution (2001-Present)

<div class="row mt-3">
    <div class="col-12 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/BT_LLM/timeline.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    This graphic depicts milestone achievements in the history of AI development over the past 60 years in the form of a river diagram. The original author is AMiner {% cite Tang20 %}.
</div>

The exponential growth of computational power and the internet in the early 21st century enabled the creation of massive datasets, driving significant advancements in AI. Deep learning, utilizing multi-layered neural networks, revolutionized AI research, with Geoffrey Hinton's work  {% cite Ba2016 %} on convolutional neural networks improving image classification and AlphaGo's victory in Go showcasing deep learning's potential.

The resurgence of neural networks led to breakthroughs in computer vision, speech recognition, and natural language processing. Innovations like convolutional neural networks (CNNs) for image recognition and transformer models for language understanding) tackled challenges in sequential data processing. These These advances revolutionized how machines perceive, interpret, and interact with data, solidifying AI's impact. Interested readers can refer to [Chapter 2]() for the henceforth stories.The main results (figures) are listed below: 
<swiper-container keyboard="true" navigation="true" pagination="true" pagination-clickable="true" pagination-dynamic-bullets="true" rewind="true">
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/BT_LLM/results/beta_time.png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/BT_LLM/results/RAG_benefit.png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/BT_LLM/results/ex1_p=0.35.png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/BT_LLM/results/ex3_p=0.4.png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/BT_LLM/results/activities_p=0.4.png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/BT_LLM/results/activities_p=0.6.png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/BT_LLM/results/self-awareness_p=0.8.png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/BT_LLM/results/Mingyue_p=0.4.png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/BT_LLM/results/Mingyue_p=0.8.png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/BT_LLM/results/misinformation_document.png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/BT_LLM/results/poisoned_knowledge.png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/BT_LLM/results/prompt_template.png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
</swiper-container>


