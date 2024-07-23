### Refinement mechanisms in synthesis

Programming is an *inherently iterative* process: when was the last time you coded a feature that worked right away without any debugging? Yet, we often assume that synthesis must be a push-a-button-once process where either you get a perfect controller from the get-go, or you are guaranteed there is no suitable one. But what happens if your specification is ill-defined and needs to be amended, or if your system needs to be patched to permit the existence of a suitable controller? This is what we are working on: techniques to *help when synthesis fails*. In particular, we are studying appropriate notions of *counter-examples* à la {% cite DBLP:conf/tacas/WimmerJABK12 -f axis_RefineRS %} to understand where a system fails and how to fix it, hence enabling synthesis through *iterative refinements*.

#### References
<div class="publications">
{% bibliography -f axis_RefineRS.bib --cited --template bib --group_by none %}
</div>


