---
layout: page
title: Formal Methods for System Design
description: Taught to Master students in mathematics and computer science.
img: assets/img/FMSD.jpg
importance: 1
category: Master
related_publications: false
---

### First semester
---

The whole course is worth 12 ECTS, and takes place over two semesters (120 hours in total). During the first semester, we focus on the *foundations* of model checking and synthesis. My notes are heavily inspired by the wonderful book *<a href="https://mitpress.mit.edu/9780262026499/principles-of-model-checking/">Principles of Model Checking</a>* by Baier & Katoen. The topics I cover are as follow:
<ul>
<li>Full course outline. <a href="/assets/pdf/toc.pdf">[PDF]</a></li>
<li>Chapter 1: Formal verification. <a href="/assets/pdf/Chapter_1_handout.pdf">[Slides]</a></li>
<li>Chapter 2: Modeling systems. <a href="/assets/pdf/Chapter_2_handout.pdf">[Slides]</a></li>
<li>Chapter 3: Linear temporal logic. <a href="/assets/pdf/Chapter_3_handout.pdf">[Slides]</a></li>
<li>Chapter 4: Computation tree logic. <a href="/assets/pdf/Chapter_4_handout.pdf">[Slides]</a></li>
<li>Chapter 5: Symbolic model checking. <a href="/assets/pdf/Chapter_5_handout.pdf">[Slides]</a></li>
<li>Chapter 6: Model checking probabilistic systems. <a href="/assets/pdf/Chapter_6_handout.pdf">[Slides]</a></li>
<li>Chapter 7: Synthesis through game theory.</li>
</ul>

There are no slides for Chapter 7: I use a flipped classroom approach, focusing on a chapter of the *<a href="https://link.springer.com/book/10.1007/978-3-319-10575-8">Handbook of Model Checking</a>*. Students read the chapter in autonomy and we discuss it together. 

During the first semester, students also learn to use model checking and verification tools such as <a href="https://spinroot.com/spin/whatispin.html">SPIN</a>, <a href="https://uppaal.org/">Uppaal</a>, <a href="https://www.stormchecker.org/">Storm</a> or <a href="https://www.prismmodelchecker.org/">Prism</a>.


### Second semester
---

There are no classical lectures during the second semester. Two activities take place in parallel.

First, students prepare and give lectures on an advanced topic of their choice, helped in their preparation by the teaching team. We obviously focus on the understanding of the subject, but also stress on the pedagogical quality of the lectures.

Second, students take part in a semester-long project mixing AI (reinforcement learning in particular) and formal methods. The ecosystem of choice is <a href="https://gymnasium.farama.org/index.html">Gymnasium</a>, a standard API for RL that essentially offers a playground to synthesize and assess controllers in various environments. We coach the students through regular meetings (roughly every ten days) where they present their progress, their difficulties, etc. We start by exploring classical methods in RL and model checking and reach advanced techniques (and difficult environments, such as the Lunar Lander below) by the end of the semester.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/LunarLander.gif" title="Lunar Lander" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
