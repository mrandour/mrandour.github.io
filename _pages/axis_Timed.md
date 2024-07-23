### Continuous and timed systems
A key decision in modeling real-world systems is *how we handle time*: either as a *sequence of discrete steps* with events only happening at predefined ticks or as a *continuous flow* where events can take place at any point. While the second model is arguably more realistic (which can be necessary for time-sensitive applications), the resulting models are usually more difficult to analyze, often leading to undecidability when combined with complex specifications. Our team focuses on developing expressive frameworks while maintaining tractability through novel concepts, both in timed automata and games {% cite DBLP:conf/formats/MainRS22 DBLP:conf/concur/MainRS21 -f axis_Timed %}, and in hybrid systems {% cite DBLP:journals/iandc/BouyerBRRV22 -f axis_Timed %}.

#### References
<div class="publications">
{% bibliography -f axis_Timed.bib --cited --template bib --group_by none %}
</div>


