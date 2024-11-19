---
layout: page
title: ControlleRS
description: Controllers in Many-sided Reactive Synthesis - A Strategic Perspective
img: assets/img/ControlleRS.jpg
importance: 1
category: AI & Formal Methods
related_publications: false
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
  <li><a href="http://www.frs-fnrs.be/">FNRS</a> Research Project. </li>
  <li>Project leader: Mickael Randour.</li>
  <li>Duration: January 2023 to December 2026. Budget ~270.000 euros.</li>
  <li><strong style="color:Crimson;">Postdoctoral positions are available: contact me!</strong> Here is a non-exhaustive list of possible topics:
	<ul>
		<li>multi-criteria approaches in formal methods,</li>
		<li>machine learning and AI,</li>
		<li>synthesis in stochastic systems,</li>
		<li>tool development,</li>
		<li>industrial applications.</li>
	</ul></li>
  </ul>


<h3>Project summary</h3>
<p>We live in the days of ubiquitous computing: we are surrounded by reactive (computer) systems that continuously interact with their environment through user input, sensors, etc. Their correctness is often critical, either for safety reasons (e.g., ABS for cars) or due to constraints of mass production (e.g., smartphones). Unfortunately, their development is difficult and prone to errors. Formal verification and synthesis have proved to be success stories of computer science, aiming at the automated construction of provably-safe system controllers. Many techniques take roots in the game-theoretic framework, modeling the interaction between the system and its environment as a competitive game.</p>

<p>One crucial change over the last decade is the evolution from Boolean to quantitative specifications, giving birth to models describing performance of systems. Recent research focuses on taking into account the interplay between different quantitative (or qualitative) aspects and the resulting trade-offs. Such trade-offs may occur between different resources (e.g., decreasing response time requires additional computing power and energy consumption) but also between different behavioral models (e.g., average-case vs. worst-case performance). Those interactions are at the core of practical scenarios and require developers to decide how to balance the different aspects. My research group is at the forefront of research on many-sided synthesis, which supports such multi-objective reasoning.</p>
<p>The goal of ControlleRS is to challenge the key concept of strategy, currently based on automata-like finite-state machines acting as blueprints for implementable controllers. I aim to broaden the theoretical understanding and the practical usefulness of this abstract concept through the systematic study of alternative strategy models over the complete span from theoretical power to proper applicability. This endeavor promises fundamental advances toward truly implementable many-sided synthesis.</p>


<h3>Publications supported by the project: 6</h3>

<div class="publications">
 {% bibliography -f controllers --template bib --group_by type --group_order descending,descending %}
</div>


