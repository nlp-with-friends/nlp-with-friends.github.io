---
permalink: /speakers/hongming-zhang
title: "Commonsense Reasoning from the Angle of Eventualities"
speaker: Hongming Zhang
author: Hongming Zhang
time: 14:00 UTC
timeconverter: "https://www.timeanddate.com/worldclock/converter.html?iso=20200902T140000&p1=1440&p2=224&p3=179&p4=136&p5=676&p6=33&p7=152"
date: Sept 30, 2020
bio: "Hongming is a third-year Ph.D. student at HKUST and a visiting scholar at UPenn and has received Hong Kong Ph.D. Fellowship and Microsoft Research Asia Fellowship to support his research on commonsense reasoning and open domain event understanding."
read_time: true
author_profile: true
layout: single
---

<a href="https://lolmythesis.com/" class="one-line">Commonsense Knowledge is crucial for AI systems. But wait, what is commonsense exactly?</a>

Commonsense knowledge acquisition and reasoning have long been a core artificial intelligence problem. However, in the past, there has been a lack of scalable methods to collect commonsense knowledge. One important reason for that we do not have a clear definition of commonsense knowledge. In this talk, I will introduce how to understand commonsense knowledge from the angle of eventualities (i.e., events and states) and how can we acquire large-scale commonsense knowledge at a low cost.

In the beginning, I will first show that even though current pre-trained LMs have been shown capable of understanding some basic commonsense knowledge, they still cannot understand complex ones (e.g., commonsense knowledge involving multiple events). After that, I will introduce how to represent commonsense knowledge with higher-order selectional preference, which is a common phenomenon in human languages,  over eventualities. Compared with previous commonsense knowledge definition (e.g., ConceptNet), the selectional preference (SP) knowledge only relies on statistical distribution over linguistic graphs, which can be easily and accurately acquired from the unlabeled corpus with modern tools and thus makes the large-scale commonsense knowledge acquisition possible.

Following this direction, I will then introduce how to create such a large-scale eventuality-centric knowledge graph ASER, which can be easily extended to unseen eventualities with the help of conceptualization (e.g., "Microsoft buys Github" -> "Big company acquires start-up"). In the end, I will show several primary experimental results to demonstrate that ASER has the potential to serve as the hub for commonsense reasoning. (e.g., we can acquire ASER knowledge from both text and video; the knowledge in ASER can be easily converted to ConceptNet or other human-defined types; ASER can also be used to improve pre-trained LMs' performance on tasks that require commonsense knowledge, etc..)

<hr>

**Hongming** is a third-year Ph.D. student at HKUST and a visiting scholar at UPenn and has received Hong Kong Ph.D. Fellowship and Microsoft Research Asia Fellowship to support his research on commonsense reasoning and open domain event understanding.

#### Presentation Materials
<i class="fas fa-fw fa-video"></i> [Talk Video](https://www.youtube.com/watch?v=pI-SiaKsR8w&list=PL0zsOCvKa2iEqmPV6WGhjuP-tsrUy102C&index=7){:target="_blank"}  

