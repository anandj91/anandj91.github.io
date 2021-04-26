---
title: "LifeStream: A High-Performance Stream Processing Engine for Periodic Streams"
collection: publications
permalink: /research/lifestream
date: 2021-04-19
venue: '26th International Conference on Architectural Support for Programming Languages and Operating Systems'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3445814.3446725'
---
<table style="width:100%; border: none;">
  <col width="25%" />
  <col width="25%" />
  <col width="25%" />
  <col width="25%" />
  <tr style="border: none;">
    <td style="border: none;text-align: center;">
      <a href="https://dl.acm.org/doi/abs/10.1145/3445814.3446725" class="d-inline-block p-3">
        <h1><i class="fas fa-file-alt"> Paper</i></h1>
      </a>
    </td>
    <td style="border: none;text-align: center;">
      <a href="https://1drv.ms/p/s!AgF1jYPgrJ1ohjox8HWgy3jpO0hg?e=d5OwQT" class="d-inline-block p-3">
        <h1><i class="fas fa-file-powerpoint"> Slides (lightning)</i></h1>
      </a>
    </td>
    <td style="border: none;text-align: center;">
      <a href="https://1drv.ms/p/s!AgF1jYPgrJ1ohjd3oLpdstojznHE?e=8KVlnu" class="d-inline-block p-3">
        <h1><i class="fas fa-file-powerpoint"> Slides (full)</i></h1>
      </a>
    </td>
    <td style="border: none;text-align: center;">
      <a href="https://github.com/anandj91/LifeStream" class="d-inline-block p-3">
        <h1><i class="fab fa-github-square"> <b>Code</b></i></h1>
      </a>
    </td>
  </tr>
</table>

**Abstract:** Hospitals around the world collect massive amounts of physiological data from their patients every day. Recently, there
has been an increase in research interest to subject this data to statistical analysis to gain more insights and provide
improved medical diagnoses. Such analyses require complex computations on large volumes of data, demanding efficient
data processing systems. This paper shows that currently available data processing solutions either fail to meet the
performance requirements or lack simple and flexible programming interfaces. To address this problem, we propose
LifeStream, a high-performance stream processing engine for physiological data. LifeStream hits the sweet spot between
ease of programming by providing a rich temporal query language support and performance by employing optimizations that
exploit the periodic nature of physiological data. We demonstrate that LifeStream achieves end-to-end performance up to
7.5× higher than state-of-the-art streaming engines and 3.2× than hand-optimized numerical libraries on real-world
datasets and workloads.

<table style="width:100%; border: none;">
  <col width="50%" />
  <col width="50%" />
  <tr>
    <th style="text-align: center; border: none;"><h1>Lightning talk</h1></th>
    <th style="text-align: center; border: none;"><h1>Full talk</h1></th>
  </tr>
  <tr style="border: none;">
    <td style="border: none;">
      <iframe width="640" height="360" src="https://www.youtube.com/embed/0QxHXo8_csM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </td>
    <td style="border: none;">
      <iframe width="640" height="360" src="https://www.youtube.com/embed/S1QcwACqVQA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </td>
  </tr>
</table>

<h2>Citing LifeStream</h2>
<pre class="highlight" style="white-space: pre-wrap; font-size: 11px">
@inproceedings{10.1145/3445814.3446725,
     author = {Jayarajan, Anand and Hau, Kimberly and Goodwin, Andrew and Pekhimenko, Gennady},
     title = {LifeStream: A High-Performance Stream Processing Engine for Periodic Streams},
     year = {2021},
     isbn = {9781450383172},
     publisher = {Association for Computing Machinery},
     address = {New York, NY, USA},
     url = {https://doi.org/10.1145/3445814.3446725},
     doi = {10.1145/3445814.3446725},
     booktitle = {Proceedings of the 26th ACM International Conference on Architectural Support for Programming Languages and Operating Systems},
     pages = {107–122},
     numpages = {16},
     keywords = {physiological data, locality tracing, temporal query processing, event lineage tracking, stream data analytics, targeted query processing},
     location = {Virtual, USA},
     series = {ASPLOS 2021}
}
</pre>
