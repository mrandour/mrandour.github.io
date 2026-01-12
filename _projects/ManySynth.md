---
layout: page
title: ManySynth
description: Many-sided Synthesis of Reactive Systems - Foundations, Algorithms, and Tools.
img: assets/img/ManySynth.jpg
importance: 2
category: AI & Formal Methods
related_publications: no
---

<div class="row justify-content-center">
    <div class="col-sm-3 mt-4 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/UMONS-EN.png" title="UMONS" class="img-fluid" %}
    </div>
    <div class="col-sm-2 mt-4 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/fnrs.png" title="FNRS" class="img-fluid" %}
    </div>
</div>

<h3>Project highlights</h3>
<ul>
  <li><a href="http://www.frs-fnrs.be/">FNRS</a> Incentive Grant for Scientific Research. </li>
  <li>Project leader: Mickael Randour.</li>
  <li>Duration: January 2018 to December 2019. Budget ~250.000 euros.</li>
  </ul>


<h3>Project summary</h3>
<p>We live in the days of ubiquitous computing: we are surrounded by reactive
(computer) systems that continuously interact with their environment
through user input, sensors, etc. Their correctness is often critical, either for
safety reasons (e.g., ABS for cars) or due to constraints of mass production
(e.g., smartphones). Unfortunately, their development is difficult and prone
to errors. Formal verification and synthesis have proved to be success
stories of computer science, aiming at the automated construction of
provably-safe system controllers. Many techniques take roots in the game-
theoretic framework, modeling the interaction between the system and its
environment as a competitive game.</p>

<p>One crucial change over the last decade is the evolution from Boolean to
quantitative specifications, giving birth to models describing performance of
systems. However, prevalent frameworks only permit to consider a single
quantitative (or qualitative) aspect at a time: they do not take into account
their interplay and the resulting trade-offs. Such trade-offs may occur
between different resources (e.g., decreasing response time requires
additional computing power and energy consumption) but also between
different behavioral models (e.g., average-case vs. worst-case
performance). Those interactions are at the core of practical scenarios and
require the developers to decide how to balance the different aspects.
Hence, there is an absolute need for frameworks and tools capable of
modeling interplays for the synthesis approach to be effective in practice. I
coin the term “many-sided models” for such rich models in opposition to
single-sided ones, which only allow to reason about a unique aspect of
reactive systems.</p>
<p>The goal of ManySynth is to allow next-generation synthesis by establishing
formal foundations, algorithms, and tools to support the paradigm shift from
single-sided qualitative and quantitative models to many-sided ones,
developing fundamental advances in this direction. </p>


<h3>Publications supported by the project: 19 (2 best paper awards, 1 book)</h3>

<div class="publications">
 {% bibliography -f manysynth --template bib --group_by type --group_order descending,descending %}
</div>


