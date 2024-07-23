### Controller representations and complexity

In the *game-theoretic approach* toward controller synthesis, we model the interaction between a system to control and its environment as (some variation of) game between these entities, and we are looking for an appropriate (e.g., winning or optimal) **strategy** of the system. This strategy then constitutes a *formal blueprint* for a real-world controller for the system {% cite randourECCS Clarke2018  -f axis_ControlleRS %}.

The general consensus is that simple (e.g., using limited memory) strategies are better: corresponding controllers will be easier to conceive and understand, and cheaper to produce and maintain. Yet, the traditional formal model used to represent strategies is some sort of *finite automaton* {% cite DBLP:journals/corr/abs-2305-10546 -f axis_ControlleRS %}, which is usually far from what we expect in practice. In particular, our theoretical measures of strategy complexity are somewhat disconnected from what can be considered as complex or not in implemented controllers. Hence, we challenge the key concept of strategy and how to assess their complexity, and we study alternative strategy models (e.g., augmented automata, decision trees, RNNs) over the complete span from theoretical power to proper applicability. My [FNRS project ControlleRS](/projects/ControlleRS/) is dedicated to this research program.

#### References
<div class="publications">
{% bibliography -f axis_ControlleRS --cited --template bib --group_by none %}
</div>

