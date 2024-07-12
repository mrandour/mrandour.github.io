---
layout: page
title: Team
permalink: /team/
description: I am lucky to be working with amazing people.
nav: true
nav_order: 1
positions: [Postdoc, PhD, Master, Alumni]
---

<div class="people">
  {%- for position in page.positions %}
  {%- if position == "Alumni" %}
    {%- assign categorized_people = site.data.people | where_exp:"item", "item.former != nil" -%}
    {%- assign sorted_people = categorized_people | sort: "exit_year" | reverse %}
  {%- else -%}
    {%- assign categorized_people = site.data.people | where: "position", position | where: "former", nil -%}
    {%- assign sorted_people = categorized_people | sort: "start_year"  %}
  {%- endif -%}
  {% assign n = sorted_people | size %}
    {%- if n > 0 %}
    <h2 class="category">{{ position }}</h2>
    {%- endif -%}
    {%- for member in sorted_people -%}
      {% include people.liquid %}
    {%- endfor %}
  {% endfor %}
</div>
