---
permalink: /speakers/paul-michel
title: "Modeling the Second Player in Distributionally Robust Optimization"
speaker: Paul Michel
author: Paul Michel
date: Nov 4, 2020
time: 14:00 UTC
timeconverter: "https://www.timeanddate.com/worldclock/converter.html?iso=20201104T140000&p1=1440&p2=224&p3=179&p4=136&p5=676&p6=33&p7=152"
read_time: true
layout: single
author_profile: true
---

<a href="https://lolmythesis.com/" class="one-line">A classifier and a language model are put head-to-head in a ferocious face-off, distributional robustness ensues.</a>

Distributionally robust optimization (DRO) provides a framework for training machine learning models that are able to perform well on a collection of related data distributions (the "uncertainty set"). This is done by solving a min-max game: the model is trained to minimize its maximum expected loss among all distributions in the uncertainty set. While careful design of the uncertainty set is critical to the success of the DRO procedure, previous work has been limited to relatively simple alternatives that keep the min-max optimization problem exactly tractable, such as f-divergence balls. In this talk, I will argue instead for the use of neural generative models (eg. language models) to characterize the worst-case distribution, allowing for more flexible and problem-specific selection of the uncertainty set. However, while simple conceptually, this approach poses a number of implementation and optimization challenges. To circumvent these issues, we propose a relaxation of the KL-constrained inner maximization objective that makes the DRO problem more amenable to gradient-based optimization of large scale generative models, and develop model selection heuristics to guide hyper-parameter search. On both toy settings and realistic NLP tasks, we find that the proposed approach yields models that are more robust than comparable baselines.

<hr>

**Paul** is a 5th year PhD student at Carnegie Mellon University. He works on training NLP models in the face of distributional shift.