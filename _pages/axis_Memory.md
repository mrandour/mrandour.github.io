### Memory bounds


The vast majority of simple objectives (which encode specifications) in two-player (stochastic) games admit *memoryless* optimal strategies. That is, controllers for the system only need to look at the current state to act optimally, regardless of what happened in the past. This usually does not hold when considering more complex objectives, such as, e.g., conjunctions of simple objectives, which are needed to accurately model the richness of real-world situations. An important research area is therefore devoted to *understanding for which objectives we need memory* and *how much*. We notably characterize the objectives for which *arena-independent* memory suffices, in a variety of settings {% cite DBLP:conf/fsttcs/BouyerRV22 DBLP:journals/theoretics/BouyerRV23 DBLP:journals/lmcs/BouyerORV23 DBLP:journals/lmcs/BouyerRORV22 -f axis_Memory %}, or provide tight bounds for specific types of objectives {% cite DBLP:conf/concur/BouyerCRV22 -f axis_Memory %}.


#### References
<div class="publications">
{% bibliography -f axis_Memory --cited --template bib --group_by none %}
</div>

