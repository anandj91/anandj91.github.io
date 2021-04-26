---
title: "LifeStream: A High-Performance Stream Processing Engine for Periodic Streams"
collection: publications
permalink: /research/lifestream
date: 2021-04-19
venue: '26th International Conference on Architectural Support for Programming Languages and Operating Systems'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3445814.3446725'
---
Hospitals around the world collect massive amounts of physiological data from their patients every day. Recently, there
has been an increase in research interest to subject this data to statistical analysis to gain more insights and provide
improved medical diagnoses. Such analyses require complex computations on large volumes of data, demanding efficient
data processing systems. This paper shows that currently available data processing solutions either fail to meet the
performance requirements or lack simple and flexible programming interfaces. To address this problem, we propose
LifeStream, a high-performance stream processing engine for physiological data. LifeStream hits the sweet spot between
ease of programming by providing a rich temporal query language support and performance by employing optimizations that
exploit the periodic nature of physiological data. We demonstrate that LifeStream achieves end-to-end performance up to
7.5× higher than state-of-the-art streaming engines and 3.2× than hand-optimized numerical libraries on real-world
datasets and workloads.
