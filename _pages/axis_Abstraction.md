### Abstractions
Abstraction is at the core of formal methods: we analyze complex systems by looking at *simplified versions* of them. Yet, it is often the case that the first formal model we work with is not abstract enough, and that we need to keep abstracting even further to enable effective model checking or synthesis. It may be necessary because the model under study is simply *too large* for practical purposes, or possesses *complex features* that are difficult to handle with classical techniques (e.g., continuous state spaces). Hence, several axes described on this page involve dealing with *abstractions as a key mechanism*. We notably use it to provide faster algorithms for classical problems (à la {% cite DBLP:journals/fmsd/KattenbeltKNP10 -f axis_Abstraction %}), or to enable guarantee-driven reasoning in continuous models (à la {% cite DBLP:conf/hybrid/WoodingL24 -f axis_Abstraction %}).

#### References
<div class="publications">
{% bibliography -f axis_Abstraction.bib --cited --template bib --group_by none %}
</div>


